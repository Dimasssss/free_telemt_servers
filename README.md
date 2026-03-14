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

# Server Metrics 2026-03-14 07:12:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 171572.4 (47h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 658182
telemt_connections_bad_total 32378
telemt_handshake_timeouts_total 13061
telemt_upstream_connect_attempt_total 43682
telemt_upstream_connect_success_total 43462
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 43682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5682
telemt_me_reconnect_attempts_total 39226
telemt_me_reconnect_success_total 34534
telemt_me_reader_eof_total 36918
telemt_me_idle_close_by_peer_total 36917
telemt_me_route_drop_no_conn_total 217340
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559870
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2090
telemt_desync_full_logged_total 715
telemt_desync_suppressed_total 1375
telemt_desync_frames_bucket_total{bucket="1_2"} 450
telemt_desync_frames_bucket_total{bucket="3_10"} 767
telemt_desync_frames_bucket_total{bucket="gt_10"} 873
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 35051
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34514
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 559755
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 16348866194 (15.23 GB)
telemt_user_octets_to_client{user="hello"} 269497546408 (250.99 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 171465.0 (47h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331670
telemt_connections_bad_total 2326
telemt_handshake_timeouts_total 2547
telemt_upstream_connect_attempt_total 150450
telemt_upstream_connect_success_total 149181
telemt_upstream_connect_fail_total 1269
telemt_upstream_connect_attempts_per_request{bucket="1"} 150450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1269
telemt_me_keepalive_timeout_total 4018
telemt_me_reconnect_attempts_total 177923
telemt_me_reconnect_success_total 37333
telemt_me_reader_eof_total 42725
telemt_me_idle_close_by_peer_total 42725
telemt_me_route_drop_no_conn_total 109367
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210883
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
telemt_me_writer_removed_unexpected_total 42074
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 37316
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4741
telemt_user_connections_total{user="hello"} 313991
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 3264844531 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 102658838215 (95.61 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 171429.3 (47h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387553
telemt_connections_bad_total 3074
telemt_handshake_timeouts_total 35158
telemt_upstream_connect_attempt_total 45195
telemt_upstream_connect_success_total 45186
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24457
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3486
telemt_me_reconnect_attempts_total 37889
telemt_me_reconnect_success_total 36603
telemt_me_reader_eof_total 39362
telemt_me_idle_close_by_peer_total 39362
telemt_me_route_drop_no_conn_total 139930
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335831
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
telemt_me_writer_removed_unexpected_total 37045
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36582
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 335603
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 13518393452 (12.59 GB)
telemt_user_octets_to_client{user="hello"} 133322652660 (124.17 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 171404.1 (47h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 489515
telemt_connections_bad_total 16260
telemt_handshake_timeouts_total 4526
telemt_upstream_connect_attempt_total 75639
telemt_upstream_connect_success_total 65058
telemt_upstream_connect_fail_total 10581
telemt_upstream_connect_attempts_per_request{bucket="1"} 75639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10581
telemt_me_keepalive_timeout_total 5405
telemt_me_reconnect_attempts_total 143546
telemt_me_reconnect_success_total 37485
telemt_me_reader_eof_total 42017
telemt_me_idle_close_by_peer_total 42009
telemt_me_route_drop_no_conn_total 176795
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416681
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1776
telemt_desync_full_logged_total 530
telemt_desync_suppressed_total 1246
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 41226
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 37475
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3741
telemt_user_connections_total{user="hello"} 435544
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 9417410795 (8.77 GB)
telemt_user_octets_to_client{user="hello"} 178544157624 (166.28 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 121575.8 (33h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198097
telemt_connections_bad_total 29329
telemt_handshake_timeouts_total 1736
telemt_upstream_connect_attempt_total 42886
telemt_upstream_connect_success_total 42475
telemt_upstream_connect_fail_total 410
telemt_upstream_connect_attempts_per_request{bucket="1"} 42885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 410
telemt_me_keepalive_timeout_total 2526
telemt_me_reconnect_attempts_total 44970
telemt_me_reconnect_success_total 31539
telemt_me_reader_eof_total 33760
telemt_me_idle_close_by_peer_total 33760
telemt_me_route_drop_no_conn_total 59029
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156756
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 656
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 497
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 321
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 32249
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31521
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 710
telemt_user_connections_total{user="hello"} 161505
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 2402567409 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 74878691819 (69.74 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 171360.3 (47h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 980018
telemt_connections_bad_total 36071
telemt_handshake_timeouts_total 26080
telemt_upstream_connect_attempt_total 35564
telemt_upstream_connect_success_total 35375
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 35564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 4720
telemt_me_reconnect_attempts_total 31572
telemt_me_reconnect_success_total 26893
telemt_me_reader_eof_total 28871
telemt_me_idle_close_by_peer_total 28868
telemt_me_route_drop_no_conn_total 461874
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908596
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
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 27380
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26886
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 881240
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 15139612292 (14.10 GB)
telemt_user_octets_to_client{user="hello"} 445079913868 (414.51 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 76
```