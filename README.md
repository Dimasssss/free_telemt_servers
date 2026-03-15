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

# Server Metrics 2026-03-15 11:29:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 47678.9 (13h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203923
telemt_connections_bad_total 1389
telemt_handshake_timeouts_total 4420
telemt_upstream_connect_attempt_total 12109
telemt_upstream_connect_success_total 12045
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 12051
telemt_me_reconnect_success_total 9674
telemt_me_reader_eof_total 10311
telemt_me_idle_close_by_peer_total 10311
telemt_me_route_drop_no_conn_total 418935
telemt_me_route_drop_channel_closed_total 64
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251029
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1472
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 888
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 584
telemt_desync_frames_bucket_total{bucket="gt_10"} 646
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9839
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 9643
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 190286
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 3611579484 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 187200923200 (174.34 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 47685.5 (13h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67833
telemt_connections_bad_total 2334
telemt_handshake_timeouts_total 3425
telemt_upstream_connect_attempt_total 12858
telemt_upstream_connect_success_total 12858
telemt_upstream_connect_attempts_per_request{bucket="1"} 12858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12793
telemt_me_reconnect_success_total 10466
telemt_me_reader_eof_total 11221
telemt_me_idle_close_by_peer_total 11221
telemt_me_route_drop_no_conn_total 31685
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59858
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10651
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 10450
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 59857
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 1092302388 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 24645686024 (22.95 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 47678.3 (13h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75224
telemt_connections_bad_total 1010
telemt_handshake_timeouts_total 2548
telemt_upstream_connect_attempt_total 13543
telemt_upstream_connect_success_total 13535
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 13543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 12354
telemt_me_reconnect_success_total 11146
telemt_me_reader_eof_total 11921
telemt_me_idle_close_by_peer_total 11921
telemt_me_route_drop_no_conn_total 28668
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68411
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 11284
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11138
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 68329
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 9472456792 (8.82 GB)
telemt_user_octets_to_client{user="hello"} 42735110020 (39.80 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 47677.8 (13h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99902
telemt_connections_bad_total 287
telemt_handshake_timeouts_total 672
telemt_upstream_connect_attempt_total 11263
telemt_upstream_connect_success_total 11262
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 8942
telemt_me_reconnect_success_total 8898
telemt_me_reader_eof_total 9489
telemt_me_idle_close_by_peer_total 9489
telemt_me_route_drop_no_conn_total 40320
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91261
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 208
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8994
telemt_me_writer_restored_same_endpoint_total 8887
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 91182
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 1697810504 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 52995869140 (49.36 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 22749.2 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43917
telemt_connections_bad_total 6519
telemt_handshake_timeouts_total 838
telemt_upstream_connect_attempt_total 7638
telemt_upstream_connect_success_total 7581
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 7638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 100658
telemt_me_reconnect_success_total 6244
telemt_me_reader_eof_total 6489
telemt_me_idle_close_by_peer_total 6489
telemt_me_route_drop_no_conn_total 18006
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35436
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 70
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 6229
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6140
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 35574
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 546352421 (521.04 MB)
telemt_user_octets_to_client{user="hello"} 14019934959 (13.06 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 47677.1 (13h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264117
telemt_connections_bad_total 44961
telemt_handshake_timeouts_total 2001
telemt_upstream_connect_attempt_total 10121
telemt_upstream_connect_success_total 10059
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 10121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 7730
telemt_me_reconnect_success_total 7682
telemt_me_reader_eof_total 8184
telemt_me_idle_close_by_peer_total 8184
telemt_me_route_drop_no_conn_total 117620
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209396
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 7744
telemt_me_writer_restored_same_endpoint_total 7655
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 207764
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 4737193612 (4.41 GB)
telemt_user_octets_to_client{user="hello"} 100202958868 (93.32 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 59
```