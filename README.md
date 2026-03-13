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

# Server Metrics 2026-03-13 18:08:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 124516.5 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525931
telemt_connections_bad_total 9122
telemt_handshake_timeouts_total 12117
telemt_upstream_connect_attempt_total 31269
telemt_upstream_connect_success_total 31114
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 31269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3460
telemt_me_reconnect_attempts_total 29514
telemt_me_reconnect_success_total 24872
telemt_me_reader_eof_total 26562
telemt_me_idle_close_by_peer_total 26561
telemt_me_route_drop_no_conn_total 171978
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 456653
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1468
telemt_desync_full_logged_total 508
telemt_desync_suppressed_total 960
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 25291
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 24856
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 456221
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 8404698212 (7.83 GB)
telemt_user_octets_to_client{user="hello"} 215572247204 (200.77 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 124410.0 (34h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259935
telemt_connections_bad_total 1951
telemt_handshake_timeouts_total 1835
telemt_upstream_connect_attempt_total 113022
telemt_upstream_connect_success_total 112170
telemt_upstream_connect_fail_total 852
telemt_upstream_connect_attempts_per_request{bucket="1"} 113022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1638
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 852
telemt_me_keepalive_timeout_total 1518
telemt_me_reconnect_attempts_total 128544
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29990
telemt_me_idle_close_by_peer_total 29990
telemt_me_route_drop_no_conn_total 82894
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166482
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 31
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
telemt_me_writer_removed_unexpected_total 29460
telemt_me_refill_failed_total 3199
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3427
telemt_user_connections_total{user="hello"} 246180
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 2565949362 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 75908905691 (70.70 GB)
telemt_user_msgs_from_client{user="hello"} 1255486
telemt_user_msgs_to_client{user="hello"} 7339139
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 124373.6 (34h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306699
telemt_connections_bad_total 2552
telemt_handshake_timeouts_total 18034
telemt_upstream_connect_attempt_total 33183
telemt_upstream_connect_success_total 33179
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 33183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17758
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2677
telemt_me_reconnect_attempts_total 28136
telemt_me_reconnect_success_total 26907
telemt_me_reader_eof_total 28858
telemt_me_idle_close_by_peer_total 28858
telemt_me_route_drop_no_conn_total 109477
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275328
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 27206
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26887
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 275240
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 10245947612 (9.54 GB)
telemt_user_octets_to_client{user="hello"} 112945108936 (105.19 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 124348.6 (34h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 412855
telemt_connections_bad_total 15113
telemt_handshake_timeouts_total 3879
telemt_upstream_connect_attempt_total 60517
telemt_upstream_connect_success_total 50262
telemt_upstream_connect_fail_total 10255
telemt_upstream_connect_attempts_per_request{bucket="1"} 60517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10255
telemt_me_keepalive_timeout_total 4674
telemt_me_reconnect_attempts_total 114657
telemt_me_reconnect_success_total 25001
telemt_me_reader_eof_total 28518
telemt_me_idle_close_by_peer_total 28511
telemt_me_route_drop_no_conn_total 142308
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344881
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1353
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 950
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 28119
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 24991
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3118
telemt_user_connections_total{user="hello"} 363771
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 8384192923 (7.81 GB)
telemt_user_octets_to_client{user="hello"} 129836220936 (120.92 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 74520.0 (20h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122790
telemt_connections_bad_total 15440
telemt_handshake_timeouts_total 1398
telemt_upstream_connect_attempt_total 29265
telemt_upstream_connect_success_total 28995
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 29265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 1186
telemt_me_reconnect_attempts_total 33761
telemt_me_reconnect_success_total 20373
telemt_me_reader_eof_total 21847
telemt_me_idle_close_by_peer_total 21847
telemt_me_route_drop_no_conn_total 38584
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97104
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 479
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 380
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 20976
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20355
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 102001
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 1204138445 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 34140140059 (31.80 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 124305.8 (34h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 760036
telemt_connections_bad_total 24762
telemt_handshake_timeouts_total 24494
telemt_upstream_connect_attempt_total 25835
telemt_upstream_connect_success_total 25697
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 25835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 2991
telemt_me_reconnect_attempts_total 24147
telemt_me_reconnect_success_total 19504
telemt_me_reader_eof_total 20930
telemt_me_idle_close_by_peer_total 20927
telemt_me_route_drop_no_conn_total 360509
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 713146
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 681
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 19905
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19497
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 686033
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 12030026908 (11.20 GB)
telemt_user_octets_to_client{user="hello"} 341218541856 (317.78 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 67
```