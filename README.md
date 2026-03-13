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

# Server Metrics 2026-03-13 08:24:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 89477.4 (24h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347540
telemt_connections_bad_total 3175
telemt_handshake_timeouts_total 7613
telemt_upstream_connect_attempt_total 22396
telemt_upstream_connect_success_total 22290
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 22396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1661
telemt_me_reconnect_attempts_total 21302
telemt_me_reconnect_success_total 17795
telemt_me_reader_eof_total 19036
telemt_me_idle_close_by_peer_total 19035
telemt_me_route_drop_no_conn_total 108358
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296678
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 976
telemt_desync_full_logged_total 361
telemt_desync_suppressed_total 615
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 18093
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17779
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 296372
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 4874450280 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 135754445872 (126.43 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 89370.2 (24h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158270
telemt_connections_bad_total 1493
telemt_handshake_timeouts_total 1204
telemt_upstream_connect_attempt_total 45258
telemt_upstream_connect_success_total 44642
telemt_upstream_connect_fail_total 616
telemt_upstream_connect_attempts_per_request{bucket="1"} 45258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 512
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 616
telemt_me_keepalive_timeout_total 684
telemt_me_reconnect_attempts_total 79042
telemt_me_reconnect_success_total 23671
telemt_me_reader_eof_total 26105
telemt_me_idle_close_by_peer_total 26105
telemt_me_route_drop_no_conn_total 59577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132833
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
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
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 25592
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 23656
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1921
telemt_user_connections_total{user="hello"} 149323
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 1550687768 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 48058334031 (44.76 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 89334.1 (24h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190948
telemt_connections_bad_total 1993
telemt_handshake_timeouts_total 3363
telemt_upstream_connect_attempt_total 24222
telemt_upstream_connect_success_total 24219
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 579
telemt_me_reconnect_attempts_total 20884
telemt_me_reconnect_success_total 19702
telemt_me_reader_eof_total 21130
telemt_me_idle_close_by_peer_total 21130
telemt_me_route_drop_no_conn_total 73431
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178562
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 19921
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19682
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 178492
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 6652421960 (6.20 GB)
telemt_user_octets_to_client{user="hello"} 75391016216 (70.21 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 89309.5 (24h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276886
telemt_connections_bad_total 13652
telemt_handshake_timeouts_total 2067
telemt_upstream_connect_attempt_total 37041
telemt_upstream_connect_success_total 27074
telemt_upstream_connect_fail_total 9967
telemt_upstream_connect_attempts_per_request{bucket="1"} 37041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9967
telemt_me_keepalive_timeout_total 3381
telemt_me_reconnect_attempts_total 71284
telemt_me_reconnect_success_total 19738
telemt_me_reader_eof_total 21984
telemt_me_idle_close_by_peer_total 21977
telemt_me_route_drop_no_conn_total 99834
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235284
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 859
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 606
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 21606
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 19728
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1868
telemt_user_connections_total{user="hello"} 238010
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 5270995506 (4.91 GB)
telemt_user_octets_to_client{user="hello"} 90401315837 (84.19 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 39481.0 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49712
telemt_connections_bad_total 8035
telemt_handshake_timeouts_total 413
telemt_upstream_connect_attempt_total 13624
telemt_upstream_connect_success_total 13487
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 13624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 12489
telemt_me_reconnect_success_total 11519
telemt_me_reader_eof_total 12237
telemt_me_idle_close_by_peer_total 12237
telemt_me_route_drop_no_conn_total 14907
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39883
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11648
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 11501
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 39882
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 285045676 (271.84 MB)
telemt_user_octets_to_client{user="hello"} 11344734024 (10.57 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 89266.2 (24h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473893
telemt_connections_bad_total 13325
telemt_handshake_timeouts_total 4213
telemt_upstream_connect_attempt_total 18887
telemt_upstream_connect_success_total 18785
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 18887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 1529
telemt_me_reconnect_attempts_total 17976
telemt_me_reconnect_success_total 14335
telemt_me_reader_eof_total 15401
telemt_me_idle_close_by_peer_total 15398
telemt_me_route_drop_no_conn_total 241720
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 463723
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 383
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 14631
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14328
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 439460
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 8124404328 (7.57 GB)
telemt_user_octets_to_client{user="hello"} 251961119816 (234.66 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 56
```