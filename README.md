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

# Server Metrics 2026-03-13 03:43:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 72583.6 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281434
telemt_connections_bad_total 2968
telemt_handshake_timeouts_total 5746
telemt_upstream_connect_attempt_total 18348
telemt_upstream_connect_success_total 18266
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 18348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1531
telemt_me_reconnect_attempts_total 18104
telemt_me_reconnect_success_total 14617
telemt_me_reader_eof_total 15623
telemt_me_idle_close_by_peer_total 15622
telemt_me_route_drop_no_conn_total 87475
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235108
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 784
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 494
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 353
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14885
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 14601
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 235048
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 4122479256 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 115734141968 (107.79 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 72476.5 (20h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129507
telemt_connections_bad_total 745
telemt_handshake_timeouts_total 983
telemt_upstream_connect_attempt_total 39618
telemt_upstream_connect_success_total 39139
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 39618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 503
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_keepalive_timeout_total 529
telemt_me_reconnect_attempts_total 65564
telemt_me_reconnect_success_total 19005
telemt_me_reader_eof_total 21013
telemt_me_idle_close_by_peer_total 21013
telemt_me_route_drop_no_conn_total 46772
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106531
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 20604
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 18990
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1599
telemt_user_connections_total{user="hello"} 123031
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 1283960376 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 36557418363 (34.05 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 72440.2 (20h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155789
telemt_connections_bad_total 1826
telemt_handshake_timeouts_total 2438
telemt_upstream_connect_attempt_total 20102
telemt_upstream_connect_success_total 20100
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 17587
telemt_me_reconnect_success_total 16424
telemt_me_reader_eof_total 17575
telemt_me_idle_close_by_peer_total 17575
telemt_me_route_drop_no_conn_total 60010
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145764
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
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 16603
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 16404
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 145689
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 2755720432 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 69300179840 (64.54 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 72415.7 (20h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223551
telemt_connections_bad_total 13467
telemt_handshake_timeouts_total 1443
telemt_upstream_connect_attempt_total 32405
telemt_upstream_connect_success_total 22566
telemt_upstream_connect_fail_total 9839
telemt_upstream_connect_attempts_per_request{bucket="1"} 32405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11057
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9839
telemt_me_keepalive_timeout_total 3302
telemt_me_reconnect_attempts_total 59599
telemt_me_reconnect_success_total 16072
telemt_me_reader_eof_total 17948
telemt_me_idle_close_by_peer_total 17941
telemt_me_route_drop_no_conn_total 81583
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186535
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 17649
telemt_me_refill_failed_total 1356
telemt_me_writer_restored_same_endpoint_total 16062
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1577
telemt_user_connections_total{user="hello"} 189285
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 3159040238 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 77141559781 (71.84 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 22587.5 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21944
telemt_connections_bad_total 4237
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 7082
telemt_upstream_connect_success_total 7016
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 7082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 5884
telemt_me_reconnect_success_total 5864
telemt_me_reader_eof_total 6277
telemt_me_idle_close_by_peer_total 6277
telemt_me_route_drop_no_conn_total 6358
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17048
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5912
telemt_me_writer_restored_same_endpoint_total 5846
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 17048
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 127201136 (121.31 MB)
telemt_user_octets_to_client{user="hello"} 7061638256 (6.58 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 72372.2 (20h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377110
telemt_connections_bad_total 6682
telemt_handshake_timeouts_total 2890
telemt_upstream_connect_attempt_total 15436
telemt_upstream_connect_success_total 15350
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 15436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 1423
telemt_me_reconnect_attempts_total 15364
telemt_me_reconnect_success_total 11739
telemt_me_reader_eof_total 12609
telemt_me_idle_close_by_peer_total 12606
telemt_me_route_drop_no_conn_total 169008
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368660
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 12002
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11732
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 356907
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 5992961172 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 214713374404 (199.97 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 38
```