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

# Server Metrics 2026-03-13 14:34:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 111668.5 (31h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 461869
telemt_connections_bad_total 3217
telemt_handshake_timeouts_total 8614
telemt_upstream_connect_attempt_total 28075
telemt_upstream_connect_success_total 27945
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 28075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2428
telemt_me_reconnect_attempts_total 25878
telemt_me_reconnect_success_total 22347
telemt_me_reader_eof_total 23868
telemt_me_idle_close_by_peer_total 23867
telemt_me_route_drop_no_conn_total 149918
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 404369
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1342
telemt_desync_full_logged_total 475
telemt_desync_suppressed_total 867
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 22691
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22331
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 403947
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 7311973636 (6.81 GB)
telemt_user_octets_to_client{user="hello"} 186701398288 (173.88 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 111561.3 (30h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218840
telemt_connections_bad_total 1830
telemt_handshake_timeouts_total 1550
telemt_upstream_connect_attempt_total 77404
telemt_upstream_connect_success_total 76656
telemt_upstream_connect_fail_total 747
telemt_upstream_connect_attempts_per_request{bucket="1"} 77403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 749
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 747
telemt_me_keepalive_timeout_total 1397
telemt_me_reconnect_attempts_total 108050
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29345
telemt_me_idle_close_by_peer_total 29345
telemt_me_route_drop_no_conn_total 80117
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161921
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 26
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28809
telemt_me_refill_failed_total 2559
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2787
telemt_user_connections_total{user="hello"} 206781
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 2086441845 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 66210523109 (61.66 GB)
telemt_user_msgs_from_client{user="hello"} 664136
telemt_user_msgs_to_client{user="hello"} 4486226
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 111525.0 (30h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265284
telemt_connections_bad_total 2196
telemt_handshake_timeouts_total 11364
telemt_upstream_connect_attempt_total 30021
telemt_upstream_connect_success_total 30017
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2288
telemt_me_reconnect_attempts_total 25627
telemt_me_reconnect_success_total 24410
telemt_me_reader_eof_total 26137
telemt_me_idle_close_by_peer_total 26137
telemt_me_route_drop_no_conn_total 96182
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242210
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 24678
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24390
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 242125
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 9510615748 (8.86 GB)
telemt_user_octets_to_client{user="hello"} 103759627896 (96.63 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 111500.6 (30h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364104
telemt_connections_bad_total 15043
telemt_handshake_timeouts_total 3628
telemt_upstream_connect_attempt_total 41994
telemt_upstream_connect_success_total 31862
telemt_upstream_connect_fail_total 10132
telemt_upstream_connect_attempts_per_request{bucket="1"} 41994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10132
telemt_me_keepalive_timeout_total 4141
telemt_me_reconnect_attempts_total 97081
telemt_me_reconnect_success_total 23251
telemt_me_reader_eof_total 26260
telemt_me_idle_close_by_peer_total 26253
telemt_me_route_drop_no_conn_total 130549
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 314580
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1218
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 858
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 461
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 25858
telemt_me_refill_failed_total 2302
telemt_me_writer_restored_same_endpoint_total 23241
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2607
telemt_user_connections_total{user="hello"} 317490
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 6833048454 (6.36 GB)
telemt_user_octets_to_client{user="hello"} 119755755565 (111.53 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 61672.1 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94588
telemt_connections_bad_total 12404
telemt_handshake_timeouts_total 1212
telemt_upstream_connect_attempt_total 25429
telemt_upstream_connect_success_total 25221
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 25429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 1033
telemt_me_reconnect_attempts_total 27142
telemt_me_reconnect_success_total 17220
telemt_me_reader_eof_total 18475
telemt_me_idle_close_by_peer_total 18475
telemt_me_route_drop_no_conn_total 28120
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73052
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 304
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 17679
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 17202
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 459
telemt_user_connections_total{user="hello"} 77952
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 916968193 (874.49 MB)
telemt_user_octets_to_client{user="hello"} 22531485075 (20.98 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 111457.0 (30h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 658094
telemt_connections_bad_total 18447
telemt_handshake_timeouts_total 20283
telemt_upstream_connect_attempt_total 23411
telemt_upstream_connect_success_total 23293
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 23411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2529
telemt_me_reconnect_attempts_total 22389
telemt_me_reconnect_success_total 17764
telemt_me_reader_eof_total 19073
telemt_me_idle_close_by_peer_total 19070
telemt_me_route_drop_no_conn_total 317096
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 624384
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 478
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18139
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17757
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 597334
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 10325810020 (9.62 GB)
telemt_user_octets_to_client{user="hello"} 312189398120 (290.75 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 67
```