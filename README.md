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

# Server Metrics 2026-03-13 15:10:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 113807.7 (31h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472638
telemt_connections_bad_total 3230
telemt_handshake_timeouts_total 8653
telemt_upstream_connect_attempt_total 28562
telemt_upstream_connect_success_total 28425
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15551
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2474
telemt_me_reconnect_attempts_total 26258
telemt_me_reconnect_success_total 22725
telemt_me_reader_eof_total 24278
telemt_me_idle_close_by_peer_total 24277
telemt_me_route_drop_no_conn_total 154119
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 414625
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1360
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 573
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 23072
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22709
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 414202
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 7442179444 (6.93 GB)
telemt_user_octets_to_client{user="hello"} 192629830160 (179.40 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 113700.8 (31h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225395
telemt_connections_bad_total 1833
telemt_handshake_timeouts_total 1582
telemt_upstream_connect_attempt_total 82909
telemt_upstream_connect_success_total 82138
telemt_upstream_connect_fail_total 771
telemt_upstream_connect_attempts_per_request{bucket="1"} 82909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 849
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 771
telemt_me_keepalive_timeout_total 1401
telemt_me_reconnect_attempts_total 112178
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29473
telemt_me_idle_close_by_peer_total 29473
telemt_me_route_drop_no_conn_total 81028
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162870
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 27
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
telemt_me_writer_removed_unexpected_total 28938
telemt_me_refill_failed_total 2688
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2916
telemt_user_connections_total{user="hello"} 213081
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 2156097850 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 67386839594 (62.76 GB)
telemt_user_msgs_from_client{user="hello"} 744391
telemt_user_msgs_to_client{user="hello"} 4869779
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 113664.5 (31h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272583
telemt_connections_bad_total 2426
telemt_handshake_timeouts_total 12272
telemt_upstream_connect_attempt_total 30582
telemt_upstream_connect_success_total 30578
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2324
telemt_me_reconnect_attempts_total 26058
telemt_me_reconnect_success_total 24839
telemt_me_reader_eof_total 26620
telemt_me_idle_close_by_peer_total 26620
telemt_me_route_drop_no_conn_total 98330
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248177
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 25111
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24819
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 248093
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 9561775216 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 106083461864 (98.80 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 113640.0 (31h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371841
telemt_connections_bad_total 15044
telemt_handshake_timeouts_total 3673
telemt_upstream_connect_attempt_total 42611
telemt_upstream_connect_success_total 32454
telemt_upstream_connect_fail_total 10157
telemt_upstream_connect_attempts_per_request{bucket="1"} 42611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15874
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10157
telemt_me_keepalive_timeout_total 4161
telemt_me_reconnect_attempts_total 101094
telemt_me_reconnect_success_total 23712
telemt_me_reader_eof_total 26836
telemt_me_idle_close_by_peer_total 26829
telemt_me_route_drop_no_conn_total 133463
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321898
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1251
telemt_desync_full_logged_total 372
telemt_desync_suppressed_total 879
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 472
telemt_desync_frames_bucket_total{bucket="gt_10"} 471
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26435
telemt_me_refill_failed_total 2413
telemt_me_writer_restored_same_endpoint_total 23702
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2723
telemt_user_connections_total{user="hello"} 324808
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 6889414490 (6.42 GB)
telemt_user_octets_to_client{user="hello"} 122647887217 (114.22 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 63811.4 (17h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98767
telemt_connections_bad_total 12795
telemt_handshake_timeouts_total 1234
telemt_upstream_connect_attempt_total 26098
telemt_upstream_connect_success_total 25875
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 26098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 1041
telemt_me_reconnect_attempts_total 27710
telemt_me_reconnect_success_total 17787
telemt_me_reader_eof_total 19047
telemt_me_idle_close_by_peer_total 19047
telemt_me_route_drop_no_conn_total 29678
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76681
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 366
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 293
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 18251
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 17769
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 81580
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 944495445 (900.74 MB)
telemt_user_octets_to_client{user="hello"} 24871102395 (23.16 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 113597.6 (31h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679030
telemt_connections_bad_total 20258
telemt_handshake_timeouts_total 21508
telemt_upstream_connect_attempt_total 23884
telemt_upstream_connect_success_total 23763
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 23884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 2550
telemt_me_reconnect_attempts_total 22728
telemt_me_reconnect_success_total 18102
telemt_me_reader_eof_total 19432
telemt_me_idle_close_by_peer_total 19429
telemt_me_route_drop_no_conn_total 324269
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 641770
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 503
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 18480
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18095
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 378
telemt_user_connections_total{user="hello"} 614722
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 10523971316 (9.80 GB)
telemt_user_octets_to_client{user="hello"} 320550263212 (298.54 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 74
```