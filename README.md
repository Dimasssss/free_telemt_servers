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

# Server Metrics 2026-03-14 00:35:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 147740.6 (41h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 590843
telemt_connections_bad_total 20834
telemt_handshake_timeouts_total 12850
telemt_upstream_connect_attempt_total 37620
telemt_upstream_connect_success_total 37432
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 37620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5174
telemt_me_reconnect_attempts_total 34322
telemt_me_reconnect_success_total 29650
telemt_me_reader_eof_total 31689
telemt_me_idle_close_by_peer_total 31688
telemt_me_route_drop_no_conn_total 194329
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506272
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1635
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 1077
telemt_desync_frames_bucket_total{bucket="1_2"} 352
telemt_desync_frames_bucket_total{bucket="3_10"} 613
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 30125
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 29634
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 506167
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 15455003238 (14.39 GB)
telemt_user_octets_to_client{user="hello"} 250437928752 (233.24 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 147633.5 (41h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303628
telemt_connections_bad_total 2232
telemt_handshake_timeouts_total 1932
telemt_upstream_connect_attempt_total 142268
telemt_upstream_connect_success_total 141179
telemt_upstream_connect_fail_total 1089
telemt_upstream_connect_attempts_per_request{bucket="1"} 142268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1089
telemt_me_keepalive_timeout_total 3772
telemt_me_reconnect_attempts_total 157392
telemt_me_reconnect_success_total 30512
telemt_me_reader_eof_total 35267
telemt_me_idle_close_by_peer_total 35267
telemt_me_route_drop_no_conn_total 93629
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184745
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 34762
telemt_me_refill_failed_total 3959
telemt_me_writer_restored_same_endpoint_total 30495
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4250
telemt_user_connections_total{user="hello"} 287857
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 3015463787 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 89710141503 (83.55 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 147597.1 (40h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355087
telemt_connections_bad_total 2769
telemt_handshake_timeouts_total 33206
telemt_upstream_connect_attempt_total 39128
telemt_upstream_connect_success_total 39122
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 39128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21144
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2962
telemt_me_reconnect_attempts_total 32996
telemt_me_reconnect_success_total 31737
telemt_me_reader_eof_total 34088
telemt_me_idle_close_by_peer_total 34088
telemt_me_route_drop_no_conn_total 125720
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306698
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
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
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 32112
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 31717
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 306600
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 12573989504 (11.71 GB)
telemt_user_octets_to_client{user="hello"} 126284415692 (117.61 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 147572.7 (40h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456329
telemt_connections_bad_total 15364
telemt_handshake_timeouts_total 4319
telemt_upstream_connect_attempt_total 67315
telemt_upstream_connect_success_total 56889
telemt_upstream_connect_fail_total 10426
telemt_upstream_connect_attempts_per_request{bucket="1"} 67315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21819
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10426
telemt_me_keepalive_timeout_total 5048
telemt_me_reconnect_attempts_total 135488
telemt_me_reconnect_success_total 30513
telemt_me_reader_eof_total 34666
telemt_me_idle_close_by_peer_total 34658
telemt_me_route_drop_no_conn_total 160567
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386355
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1692
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 1195
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 34163
telemt_me_refill_failed_total 3274
telemt_me_writer_restored_same_endpoint_total 30503
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3650
telemt_user_connections_total{user="hello"} 405197
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 9045901423 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 155063857860 (144.41 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 97744.3 (27h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163648
telemt_connections_bad_total 23994
telemt_handshake_timeouts_total 1551
telemt_upstream_connect_attempt_total 35974
telemt_upstream_connect_success_total 35647
telemt_upstream_connect_fail_total 327
telemt_upstream_connect_attempts_per_request{bucket="1"} 35974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 327
telemt_me_keepalive_timeout_total 1356
telemt_me_reconnect_attempts_total 39287
telemt_me_reconnect_success_total 25875
telemt_me_reader_eof_total 27677
telemt_me_idle_close_by_peer_total 27677
telemt_me_route_drop_no_conn_total 48945
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128380
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 26531
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 25857
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 656
telemt_user_connections_total{user="hello"} 133216
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 1721029657 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 63581754015 (59.22 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 147528.8 (40h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 869278
telemt_connections_bad_total 27374
telemt_handshake_timeouts_total 25293
telemt_upstream_connect_attempt_total 30402
telemt_upstream_connect_success_total 30238
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 30402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 3408
telemt_me_reconnect_attempts_total 27604
telemt_me_reconnect_success_total 22939
telemt_me_reader_eof_total 24584
telemt_me_idle_close_by_peer_total 24581
telemt_me_route_drop_no_conn_total 414322
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 812025
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 702
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 473
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 23385
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22932
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 446
telemt_user_connections_total{user="hello"} 784790
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 14053426224 (13.09 GB)
telemt_user_octets_to_client{user="hello"} 401040119780 (373.50 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 35
```