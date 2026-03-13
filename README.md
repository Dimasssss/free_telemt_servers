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

# Server Metrics 2026-03-13 09:10:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 92243.8 (25h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360785
telemt_connections_bad_total 3186
telemt_handshake_timeouts_total 7819
telemt_upstream_connect_attempt_total 23337
telemt_upstream_connect_success_total 23228
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 23337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1695
telemt_me_reconnect_attempts_total 22105
telemt_me_reconnect_success_total 18594
telemt_me_reader_eof_total 19868
telemt_me_idle_close_by_peer_total 19867
telemt_me_route_drop_no_conn_total 113629
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308707
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 987
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 620
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 422
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 18898
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18578
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 308399
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 5033073764 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 138889731652 (129.35 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 92136.1 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164430
telemt_connections_bad_total 1511
telemt_handshake_timeouts_total 1242
telemt_upstream_connect_attempt_total 46074
telemt_upstream_connect_success_total 45445
telemt_upstream_connect_fail_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 46074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 514
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 629
telemt_me_keepalive_timeout_total 704
telemt_me_reconnect_attempts_total 79714
telemt_me_reconnect_success_total 24339
telemt_me_reader_eof_total 26803
telemt_me_idle_close_by_peer_total 26803
telemt_me_route_drop_no_conn_total 62995
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138398
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 26269
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 24324
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1930
telemt_user_connections_total{user="hello"} 154887
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 1600278208 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 49817021575 (46.40 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 92099.6 (25h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201037
telemt_connections_bad_total 2002
telemt_handshake_timeouts_total 4107
telemt_upstream_connect_attempt_total 24951
telemt_upstream_connect_success_total 24948
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13467
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 637
telemt_me_reconnect_attempts_total 21482
telemt_me_reconnect_success_total 20296
telemt_me_reader_eof_total 21772
telemt_me_idle_close_by_peer_total 21772
telemt_me_route_drop_no_conn_total 76035
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187490
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
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 20519
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20276
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 187415
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 6868508560 (6.40 GB)
telemt_user_octets_to_client{user="hello"} 77742886836 (72.40 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 92075.5 (25h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286802
telemt_connections_bad_total 13663
telemt_handshake_timeouts_total 2135
telemt_upstream_connect_attempt_total 38028
telemt_upstream_connect_success_total 28034
telemt_upstream_connect_fail_total 9994
telemt_upstream_connect_attempts_per_request{bucket="1"} 38028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9994
telemt_me_keepalive_timeout_total 3410
telemt_me_reconnect_attempts_total 75821
telemt_me_reconnect_success_total 20563
telemt_me_reader_eof_total 22928
telemt_me_idle_close_by_peer_total 22921
telemt_me_route_drop_no_conn_total 103417
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244640
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 902
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 637
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 336
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22550
telemt_me_refill_failed_total 1722
telemt_me_writer_restored_same_endpoint_total 20553
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1987
telemt_user_connections_total{user="hello"} 247365
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 5498224810 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 93999291373 (87.54 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 42246.9 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54531
telemt_connections_bad_total 8533
telemt_handshake_timeouts_total 456
telemt_upstream_connect_attempt_total 14678
telemt_upstream_connect_success_total 14533
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 14677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 14652
telemt_me_reconnect_success_total 12426
telemt_me_reader_eof_total 13226
telemt_me_idle_close_by_peer_total 13226
telemt_me_route_drop_no_conn_total 16519
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44058
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
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
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 12608
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12408
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 44053
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 324973164 (309.92 MB)
telemt_user_octets_to_client{user="hello"} 12057970080 (11.23 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 92031.8 (25h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493500
telemt_connections_bad_total 13437
telemt_handshake_timeouts_total 5032
telemt_upstream_connect_attempt_total 19462
telemt_upstream_connect_success_total 19358
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 19462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 1539
telemt_me_reconnect_attempts_total 18415
telemt_me_reconnect_success_total 14770
telemt_me_reader_eof_total 15862
telemt_me_idle_close_by_peer_total 15859
telemt_me_route_drop_no_conn_total 258333
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 484550
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 397
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 15075
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14763
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 305
telemt_user_connections_total{user="hello"} 457645
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 8366635084 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 258911935988 (241.13 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 59
```