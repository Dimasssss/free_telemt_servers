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

# Server Metrics 2026-03-14 03:49:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 159350.5 (44h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 620387
telemt_connections_bad_total 30492
telemt_handshake_timeouts_total 12936
telemt_upstream_connect_attempt_total 40745
telemt_upstream_connect_success_total 40542
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 40745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5545
telemt_me_reconnect_attempts_total 36894
telemt_me_reconnect_success_total 32212
telemt_me_reader_eof_total 34416
telemt_me_idle_close_by_peer_total 34415
telemt_me_route_drop_no_conn_total 201449
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 525476
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1787
telemt_desync_full_logged_total 605
telemt_desync_suppressed_total 1182
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 664
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 32710
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32192
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 525367
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 15709914738 (14.63 GB)
telemt_user_octets_to_client{user="hello"} 256742330824 (239.11 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 159243.3 (44h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313567
telemt_connections_bad_total 2266
telemt_handshake_timeouts_total 1945
telemt_upstream_connect_attempt_total 146292
telemt_upstream_connect_success_total 145126
telemt_upstream_connect_fail_total 1166
telemt_upstream_connect_attempts_per_request{bucket="1"} 146292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1166
telemt_me_keepalive_timeout_total 3854
telemt_me_reconnect_attempts_total 166892
telemt_me_reconnect_success_total 33892
telemt_me_reader_eof_total 38937
telemt_me_idle_close_by_peer_total 38937
telemt_me_route_drop_no_conn_total 98980
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194255
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 40
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
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 38368
telemt_me_refill_failed_total 4150
telemt_me_writer_restored_same_endpoint_total 33875
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4476
telemt_user_connections_total{user="hello"} 297367
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 3109431559 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 95975430523 (89.38 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 159207.2 (44h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366516
telemt_connections_bad_total 2910
telemt_handshake_timeouts_total 34785
telemt_upstream_connect_attempt_total 42190
telemt_upstream_connect_success_total 42184
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 42190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22845
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3326
telemt_me_reconnect_attempts_total 35496
telemt_me_reconnect_success_total 34222
telemt_me_reader_eof_total 36771
telemt_me_idle_close_by_peer_total 36771
telemt_me_route_drop_no_conn_total 130811
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316113
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
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 34621
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34201
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 315929
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 12670386684 (11.80 GB)
telemt_user_octets_to_client{user="hello"} 127692213656 (118.92 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 159182.6 (44h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468157
telemt_connections_bad_total 15545
telemt_handshake_timeouts_total 4401
telemt_upstream_connect_attempt_total 71903
telemt_upstream_connect_success_total 61404
telemt_upstream_connect_fail_total 10499
telemt_upstream_connect_attempts_per_request{bucket="1"} 71903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24365
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10499
telemt_me_keepalive_timeout_total 5140
telemt_me_reconnect_attempts_total 140494
telemt_me_reconnect_success_total 34449
telemt_me_reader_eof_total 38804
telemt_me_idle_close_by_peer_total 38796
telemt_me_route_drop_no_conn_total 166669
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 397139
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 38159
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 34439
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3710
telemt_user_connections_total{user="hello"} 415969
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 9137680303 (8.51 GB)
telemt_user_octets_to_client{user="hello"} 161708123300 (150.60 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 109354.1 (30h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181201
telemt_connections_bad_total 26149
telemt_handshake_timeouts_total 1601
telemt_upstream_connect_attempt_total 39628
telemt_upstream_connect_success_total 39260
telemt_upstream_connect_fail_total 368
telemt_upstream_connect_attempts_per_request{bucket="1"} 39628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 368
telemt_me_keepalive_timeout_total 2370
telemt_me_reconnect_attempts_total 42338
telemt_me_reconnect_success_total 28918
telemt_me_reader_eof_total 30944
telemt_me_idle_close_by_peer_total 30944
telemt_me_route_drop_no_conn_total 53731
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143561
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 29598
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 28900
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 680
telemt_user_connections_total{user="hello"} 148320
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 2200759869 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 68716388875 (64.00 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 159138.6 (44h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 907217
telemt_connections_bad_total 28117
telemt_handshake_timeouts_total 25427
telemt_upstream_connect_attempt_total 33079
telemt_upstream_connect_success_total 32905
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 33079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 3510
telemt_me_reconnect_attempts_total 29707
telemt_me_reconnect_success_total 25038
telemt_me_reader_eof_total 26834
telemt_me_idle_close_by_peer_total 26831
telemt_me_route_drop_no_conn_total 432462
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 848469
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 758
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 25503
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25031
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 821134
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 14362863744 (13.38 GB)
telemt_user_octets_to_client{user="hello"} 413485313780 (385.09 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 33
```