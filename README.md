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

# Server Metrics 2026-03-13 13:18:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 107089.2 (29h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440389
telemt_connections_bad_total 3213
telemt_handshake_timeouts_total 8443
telemt_upstream_connect_attempt_total 27078
telemt_upstream_connect_success_total 26951
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 27078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2402
telemt_me_reconnect_attempts_total 25129
telemt_me_reconnect_success_total 21602
telemt_me_reader_eof_total 23066
telemt_me_idle_close_by_peer_total 23065
telemt_me_route_drop_no_conn_total 141029
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383902
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1298
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 838
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 21937
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21586
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 383483
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 7006150472 (6.52 GB)
telemt_user_octets_to_client{user="hello"} 166753249436 (155.30 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 106981.8 (29h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204972
telemt_connections_bad_total 1680
telemt_handshake_timeouts_total 1508
telemt_upstream_connect_attempt_total 65566
telemt_upstream_connect_success_total 64847
telemt_upstream_connect_fail_total 719
telemt_upstream_connect_attempts_per_request{bucket="1"} 65566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 624
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 719
telemt_me_keepalive_timeout_total 1387
telemt_me_reconnect_attempts_total 101133
telemt_me_reconnect_success_total 25987
telemt_me_reader_eof_total 29095
telemt_me_idle_close_by_peer_total 29095
telemt_me_route_drop_no_conn_total 79599
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160200
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 24
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
telemt_me_writer_removed_unexpected_total 28559
telemt_me_refill_failed_total 2344
telemt_me_writer_restored_same_endpoint_total 25970
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2572
telemt_user_connections_total{user="hello"} 193506
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 1982959566 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 63297651473 (58.95 GB)
telemt_user_msgs_from_client{user="hello"} 507813
telemt_user_msgs_to_client{user="hello"} 3570945
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 106945.8 (29h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249790
telemt_connections_bad_total 2073
telemt_handshake_timeouts_total 9399
telemt_upstream_connect_attempt_total 28861
telemt_upstream_connect_success_total 28857
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15455
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2242
telemt_me_reconnect_attempts_total 24684
telemt_me_reconnect_success_total 23471
telemt_me_reader_eof_total 25144
telemt_me_idle_close_by_peer_total 25144
telemt_me_route_drop_no_conn_total 91443
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229287
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 23727
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23451
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 229204
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 9432777936 (8.78 GB)
telemt_user_octets_to_client{user="hello"} 99507085972 (92.67 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 106921.0 (29h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346782
telemt_connections_bad_total 15024
telemt_handshake_timeouts_total 3410
telemt_upstream_connect_attempt_total 40749
telemt_upstream_connect_success_total 30650
telemt_upstream_connect_fail_total 10099
telemt_upstream_connect_attempts_per_request{bucket="1"} 40749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10099
telemt_me_keepalive_timeout_total 4123
telemt_me_reconnect_attempts_total 93814
telemt_me_reconnect_success_total 22260
telemt_me_reader_eof_total 25167
telemt_me_idle_close_by_peer_total 25160
telemt_me_route_drop_no_conn_total 124138
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298322
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1098
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 776
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 418
telemt_desync_frames_bucket_total{bucket="gt_10"} 413
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 24777
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 22250
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2517
telemt_user_connections_total{user="hello"} 301233
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 6079527538 (5.66 GB)
telemt_user_octets_to_client{user="hello"} 113255098501 (105.48 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 57092.6 (15h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84731
telemt_connections_bad_total 11280
telemt_handshake_timeouts_total 1193
telemt_upstream_connect_attempt_total 24199
telemt_upstream_connect_success_total 24004
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 24199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 991
telemt_me_reconnect_attempts_total 26142
telemt_me_reconnect_success_total 16223
telemt_me_reader_eof_total 17416
telemt_me_idle_close_by_peer_total 17416
telemt_me_route_drop_no_conn_total 25256
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64659
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 173
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 16673
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16205
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 69559
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 765343053 (729.89 MB)
telemt_user_octets_to_client{user="hello"} 19748060443 (18.39 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 106877.8 (29h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619200
telemt_connections_bad_total 17880
telemt_handshake_timeouts_total 16786
telemt_upstream_connect_attempt_total 22600
telemt_upstream_connect_success_total 22485
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 22600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2504
telemt_me_reconnect_attempts_total 21796
telemt_me_reconnect_success_total 17173
telemt_me_reader_eof_total 18437
telemt_me_idle_close_by_peer_total 18434
telemt_me_route_drop_no_conn_total 302425
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 590547
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 472
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 17541
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17166
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 563595
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 9868202592 (9.19 GB)
telemt_user_octets_to_client{user="hello"} 299513209096 (278.94 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 71
```