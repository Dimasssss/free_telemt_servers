# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-14 07:28:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 172489.8 (47h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 661489
telemt_connections_bad_total 32379
telemt_handshake_timeouts_total 13067
telemt_upstream_connect_attempt_total 43930
telemt_upstream_connect_success_total 43708
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 43930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5684
telemt_me_reconnect_attempts_total 39429
telemt_me_reconnect_success_total 34736
telemt_me_reader_eof_total 37144
telemt_me_idle_close_by_peer_total 37143
telemt_me_route_drop_no_conn_total 218529
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563066
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2112
telemt_desync_full_logged_total 723
telemt_desync_suppressed_total 1389
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 774
telemt_desync_frames_bucket_total{bucket="gt_10"} 882
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 35254
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34716
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 562949
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 16378234514 (15.25 GB)
telemt_user_octets_to_client{user="hello"} 270565398032 (251.98 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 172382.7 (47h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333172
telemt_connections_bad_total 2327
telemt_handshake_timeouts_total 2568
telemt_upstream_connect_attempt_total 150738
telemt_upstream_connect_success_total 149458
telemt_upstream_connect_fail_total 1280
telemt_upstream_connect_attempts_per_request{bucket="1"} 150738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1280
telemt_me_keepalive_timeout_total 4020
telemt_me_reconnect_attempts_total 178156
telemt_me_reconnect_success_total 37565
telemt_me_reader_eof_total 42960
telemt_me_idle_close_by_peer_total 42960
telemt_me_route_drop_no_conn_total 110104
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212314
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 42309
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 37548
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4744
telemt_user_connections_total{user="hello"} 315422
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 3277200491 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 103111238719 (96.03 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 172347.2 (47h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389371
telemt_connections_bad_total 3174
telemt_handshake_timeouts_total 35193
telemt_upstream_connect_attempt_total 45472
telemt_upstream_connect_success_total 45463
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24598
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3488
telemt_me_reconnect_attempts_total 38121
telemt_me_reconnect_success_total 36835
telemt_me_reader_eof_total 39598
telemt_me_idle_close_by_peer_total 39598
telemt_me_route_drop_no_conn_total 140594
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337432
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 37281
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36814
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 446
telemt_user_connections_total{user="hello"} 337204
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 13545589276 (12.62 GB)
telemt_user_octets_to_client{user="hello"} 135156932520 (125.87 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 172322.0 (47h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491475
telemt_connections_bad_total 16261
telemt_handshake_timeouts_total 4532
telemt_upstream_connect_attempt_total 75893
telemt_upstream_connect_success_total 65299
telemt_upstream_connect_fail_total 10594
telemt_upstream_connect_attempts_per_request{bucket="1"} 75893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10594
telemt_me_keepalive_timeout_total 5416
telemt_me_reconnect_attempts_total 143741
telemt_me_reconnect_success_total 37680
telemt_me_reader_eof_total 42213
telemt_me_idle_close_by_peer_total 42205
telemt_me_route_drop_no_conn_total 177947
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418572
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1783
telemt_desync_full_logged_total 533
telemt_desync_suppressed_total 1250
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 680
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 41422
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 37670
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3742
telemt_user_connections_total{user="hello"} 437450
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 9440012011 (8.79 GB)
telemt_user_octets_to_client{user="hello"} 179781161836 (167.43 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 122493.4 (34h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199584
telemt_connections_bad_total 29494
telemt_handshake_timeouts_total 1738
telemt_upstream_connect_attempt_total 43122
telemt_upstream_connect_success_total 42708
telemt_upstream_connect_fail_total 414
telemt_upstream_connect_attempts_per_request{bucket="1"} 43122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 414
telemt_me_keepalive_timeout_total 2528
telemt_me_reconnect_attempts_total 45149
telemt_me_reconnect_success_total 31716
telemt_me_reader_eof_total 33957
telemt_me_idle_close_by_peer_total 33957
telemt_me_route_drop_no_conn_total 59497
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157990
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 689
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 522
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 32430
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31698
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 714
telemt_user_connections_total{user="hello"} 162739
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 2411174421 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 75548008439 (70.36 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 172278.1 (47h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 987493
telemt_connections_bad_total 36088
telemt_handshake_timeouts_total 26154
telemt_upstream_connect_attempt_total 35728
telemt_upstream_connect_success_total 35539
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 35728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 4720
telemt_me_reconnect_attempts_total 31693
telemt_me_reconnect_success_total 27013
telemt_me_reader_eof_total 28999
telemt_me_idle_close_by_peer_total 28996
telemt_me_route_drop_no_conn_total 464721
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 914641
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 769
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 27503
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27006
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 887285
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 15200663092 (14.16 GB)
telemt_user_octets_to_client{user="hello"} 446970261856 (416.27 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 67
```