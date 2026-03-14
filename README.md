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

# Server Metrics 2026-03-14 02:53:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 155988.0 (43h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 605764
telemt_connections_bad_total 22923
telemt_handshake_timeouts_total 12920
telemt_upstream_connect_attempt_total 39882
telemt_upstream_connect_success_total 39683
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 39882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5536
telemt_me_reconnect_attempts_total 36182
telemt_me_reconnect_success_total 31502
telemt_me_reader_eof_total 33658
telemt_me_idle_close_by_peer_total 33657
telemt_me_route_drop_no_conn_total 198573
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 518668
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1685
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1104
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 689
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 31992
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 31482
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 518559
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 15650273258 (14.58 GB)
telemt_user_octets_to_client{user="hello"} 255152631616 (237.63 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 155880.5 (43h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310095
telemt_connections_bad_total 2263
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 144961
telemt_upstream_connect_success_total 143812
telemt_upstream_connect_fail_total 1149
telemt_upstream_connect_attempts_per_request{bucket="1"} 144961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1149
telemt_me_keepalive_timeout_total 3829
telemt_me_reconnect_attempts_total 164683
telemt_me_reconnect_success_total 32708
telemt_me_reader_eof_total 37707
telemt_me_idle_close_by_peer_total 37707
telemt_me_route_drop_no_conn_total 98078
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190885
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
telemt_me_writer_removed_unexpected_total 37139
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 32691
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4431
telemt_user_connections_total{user="hello"} 293997
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 3067534403 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 92761782771 (86.39 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 155844.1 (43h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363063
telemt_connections_bad_total 2832
telemt_handshake_timeouts_total 33978
telemt_upstream_connect_attempt_total 41359
telemt_upstream_connect_success_total 41353
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 41359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22396
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3308
telemt_me_reconnect_attempts_total 34794
telemt_me_reconnect_success_total 33523
telemt_me_reader_eof_total 36025
telemt_me_idle_close_by_peer_total 36025
telemt_me_route_drop_no_conn_total 129704
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313667
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
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 33915
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 33502
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 392
telemt_user_connections_total{user="hello"} 313488
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 12633179324 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 127303013344 (118.56 GB)
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 155820.0 (43h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 464204
telemt_connections_bad_total 15380
telemt_handshake_timeouts_total 4385
telemt_upstream_connect_attempt_total 70587
telemt_upstream_connect_success_total 60107
telemt_upstream_connect_fail_total 10480
telemt_upstream_connect_attempts_per_request{bucket="1"} 70587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10480
telemt_me_keepalive_timeout_total 5110
telemt_me_reconnect_attempts_total 139329
telemt_me_reconnect_success_total 33285
telemt_me_reader_eof_total 37585
telemt_me_idle_close_by_peer_total 37577
telemt_me_route_drop_no_conn_total 164496
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393624
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
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 36990
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 33275
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3705
telemt_user_connections_total{user="hello"} 412457
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 9095591659 (8.47 GB)
telemt_user_octets_to_client{user="hello"} 159858665576 (148.88 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 105991.5 (29h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176551
telemt_connections_bad_total 25539
telemt_handshake_timeouts_total 1564
telemt_upstream_connect_attempt_total 38552
telemt_upstream_connect_success_total 38195
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 38552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_keepalive_timeout_total 2346
telemt_me_reconnect_attempts_total 41446
telemt_me_reconnect_success_total 28028
telemt_me_reader_eof_total 29993
telemt_me_idle_close_by_peer_total 29993
telemt_me_route_drop_no_conn_total 52294
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139627
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
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 28701
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 28010
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 673
telemt_user_connections_total{user="hello"} 144401
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 2074142933 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 65218260535 (60.74 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 155775.9 (43h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 895311
telemt_connections_bad_total 27813
telemt_handshake_timeouts_total 25366
telemt_upstream_connect_attempt_total 32333
telemt_upstream_connect_success_total 32162
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 32333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 3501
telemt_me_reconnect_attempts_total 29103
telemt_me_reconnect_success_total 24436
telemt_me_reader_eof_total 26183
telemt_me_idle_close_by_peer_total 26180
telemt_me_route_drop_no_conn_total 426752
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 837076
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 714
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 482
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 226
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 24896
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24429
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 809834
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 14288309324 (13.31 GB)
telemt_user_octets_to_client{user="hello"} 410725599996 (382.52 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 32
```