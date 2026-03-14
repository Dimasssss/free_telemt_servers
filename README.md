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

# Server Metrics 2026-03-14 05:46:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 166376.6 (46h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641232
telemt_connections_bad_total 32303
telemt_handshake_timeouts_total 12991
telemt_upstream_connect_attempt_total 42436
telemt_upstream_connect_success_total 42220
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 42436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5575
telemt_me_reconnect_attempts_total 38244
telemt_me_reconnect_success_total 33556
telemt_me_reader_eof_total 35876
telemt_me_idle_close_by_peer_total 35875
telemt_me_route_drop_no_conn_total 209529
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 543600
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1934
telemt_desync_full_logged_total 661
telemt_desync_suppressed_total 1273
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 705
telemt_desync_frames_bucket_total{bucket="gt_10"} 810
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 34067
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33536
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 511
telemt_user_connections_total{user="hello"} 543485
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 15960475586 (14.86 GB)
telemt_user_octets_to_client{user="hello"} 263638709288 (245.53 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 166270.4 (46h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323694
telemt_connections_bad_total 2288
telemt_handshake_timeouts_total 2346
telemt_upstream_connect_attempt_total 148725
telemt_upstream_connect_success_total 147502
telemt_upstream_connect_fail_total 1223
telemt_upstream_connect_attempts_per_request{bucket="1"} 148725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2419
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1223
telemt_me_keepalive_timeout_total 3903
telemt_me_reconnect_attempts_total 172729
telemt_me_reconnect_success_total 35917
telemt_me_reader_eof_total 41137
telemt_me_idle_close_by_peer_total 41137
telemt_me_route_drop_no_conn_total 104447
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203535
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 42
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
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 40527
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 35900
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4610
telemt_user_connections_total{user="hello"} 306642
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 3182544527 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 99831956307 (92.98 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 166234.2 (46h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376363
telemt_connections_bad_total 2964
telemt_handshake_timeouts_total 34921
telemt_upstream_connect_attempt_total 44013
telemt_upstream_connect_success_total 44004
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3411
telemt_me_reconnect_attempts_total 36971
telemt_me_reconnect_success_total 35687
telemt_me_reader_eof_total 38372
telemt_me_idle_close_by_peer_total 38372
telemt_me_route_drop_no_conn_total 135447
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325437
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
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 36120
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35666
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 325213
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 13307982500 (12.39 GB)
telemt_user_octets_to_client{user="hello"} 129533891972 (120.64 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 166209.6 (46h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478102
telemt_connections_bad_total 15653
telemt_handshake_timeouts_total 4478
telemt_upstream_connect_attempt_total 74048
telemt_upstream_connect_success_total 63501
telemt_upstream_connect_fail_total 10547
telemt_upstream_connect_attempts_per_request{bucket="1"} 74048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10547
telemt_me_keepalive_timeout_total 5315
telemt_me_reconnect_attempts_total 142247
telemt_me_reconnect_success_total 36192
telemt_me_reader_eof_total 40658
telemt_me_idle_close_by_peer_total 40650
telemt_me_route_drop_no_conn_total 171853
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 406300
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1728
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 1217
telemt_desync_frames_bucket_total{bucket="1_2"} 408
telemt_desync_frames_bucket_total{bucket="3_10"} 654
telemt_desync_frames_bucket_total{bucket="gt_10"} 666
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 39918
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 36182
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3726
telemt_user_connections_total{user="hello"} 425141
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 9242644863 (8.61 GB)
telemt_user_octets_to_client{user="hello"} 168004611860 (156.47 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 116381.1 (32h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190594
telemt_connections_bad_total 28274
telemt_handshake_timeouts_total 1659
telemt_upstream_connect_attempt_total 41548
telemt_upstream_connect_success_total 41159
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 41548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_keepalive_timeout_total 2416
telemt_me_reconnect_attempts_total 43891
telemt_me_reconnect_success_total 30465
telemt_me_reader_eof_total 32622
telemt_me_idle_close_by_peer_total 32622
telemt_me_route_drop_no_conn_total 56259
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150571
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 623
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 31162
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30447
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 697
telemt_user_connections_total{user="hello"} 155320
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 2304500117 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 70489966607 (65.65 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 166165.7 (46h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 946844
telemt_connections_bad_total 33971
telemt_handshake_timeouts_total 25874
telemt_upstream_connect_attempt_total 34515
telemt_upstream_connect_success_total 34330
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 34515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 4610
telemt_me_reconnect_attempts_total 30787
telemt_me_reconnect_success_total 26112
telemt_me_reader_eof_total 28027
telemt_me_idle_close_by_peer_total 28024
telemt_me_route_drop_no_conn_total 447224
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879136
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 26589
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26105
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 477
telemt_user_connections_total{user="hello"} 851796
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 14760458364 (13.75 GB)
telemt_user_octets_to_client{user="hello"} 435196011884 (405.31 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 53
```