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

# Server Metrics 2026-03-13 08:29:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 89784.7 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349091
telemt_connections_bad_total 3176
telemt_handshake_timeouts_total 7632
telemt_upstream_connect_attempt_total 22446
telemt_upstream_connect_success_total 22340
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 22446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1664
telemt_me_reconnect_attempts_total 21352
telemt_me_reconnect_success_total 17845
telemt_me_reader_eof_total 19086
telemt_me_idle_close_by_peer_total 19085
telemt_me_route_drop_no_conn_total 108746
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298048
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
telemt_me_writer_removed_unexpected_total 18143
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17829
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 297739
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 4893354404 (4.56 GB)
telemt_user_octets_to_client{user="hello"} 135959811276 (126.62 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 89677.4 (24h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158954
telemt_connections_bad_total 1493
telemt_handshake_timeouts_total 1205
telemt_upstream_connect_attempt_total 45318
telemt_upstream_connect_success_total 44701
telemt_upstream_connect_fail_total 616
telemt_upstream_connect_attempts_per_request{bucket="1"} 45317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 512
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 616
telemt_me_keepalive_timeout_total 688
telemt_me_reconnect_attempts_total 79102
telemt_me_reconnect_success_total 23730
telemt_me_reader_eof_total 26164
telemt_me_idle_close_by_peer_total 26164
telemt_me_route_drop_no_conn_total 59751
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133379
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
telemt_me_writer_removed_unexpected_total 25652
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 23715
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1922
telemt_user_connections_total{user="hello"} 149869
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 1553230440 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 48137646091 (44.83 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 89641.0 (24h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191691
telemt_connections_bad_total 1993
telemt_handshake_timeouts_total 3372
telemt_upstream_connect_attempt_total 24316
telemt_upstream_connect_success_total 24313
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 582
telemt_me_reconnect_attempts_total 20978
telemt_me_reconnect_success_total 19796
telemt_me_reader_eof_total 21224
telemt_me_idle_close_by_peer_total 21224
telemt_me_route_drop_no_conn_total 73651
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179270
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
telemt_me_writer_removed_unexpected_total 20015
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19776
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 179200
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 6656067864 (6.20 GB)
telemt_user_octets_to_client{user="hello"} 75453853276 (70.27 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 89616.7 (24h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278026
telemt_connections_bad_total 13652
telemt_handshake_timeouts_total 2087
telemt_upstream_connect_attempt_total 37167
telemt_upstream_connect_success_total 27200
telemt_upstream_connect_fail_total 9967
telemt_upstream_connect_attempts_per_request{bucket="1"} 37167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9967
telemt_me_keepalive_timeout_total 3381
telemt_me_reconnect_attempts_total 71410
telemt_me_reconnect_success_total 19864
telemt_me_reader_eof_total 22109
telemt_me_idle_close_by_peer_total 22102
telemt_me_route_drop_no_conn_total 100284
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236359
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 866
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 610
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 322
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 21731
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 19854
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1867
telemt_user_connections_total{user="hello"} 239085
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 5359238210 (4.99 GB)
telemt_user_octets_to_client{user="hello"} 90780770469 (84.55 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 39788.2 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50237
telemt_connections_bad_total 8090
telemt_handshake_timeouts_total 414
telemt_upstream_connect_attempt_total 13805
telemt_upstream_connect_success_total 13665
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 13805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 322
telemt_me_reconnect_attempts_total 13519
telemt_me_reconnect_success_total 11652
telemt_me_reader_eof_total 12399
telemt_me_idle_close_by_peer_total 12399
telemt_me_route_drop_no_conn_total 15061
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40338
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
telemt_me_writer_removed_unexpected_total 11810
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 11634
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 40337
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 290021040 (276.59 MB)
telemt_user_octets_to_client{user="hello"} 11409033552 (10.63 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 89573.3 (24h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475980
telemt_connections_bad_total 13340
telemt_handshake_timeouts_total 4308
telemt_upstream_connect_attempt_total 18938
telemt_upstream_connect_success_total 18836
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 18938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 1530
telemt_me_reconnect_attempts_total 18027
telemt_me_reconnect_success_total 14386
telemt_me_reader_eof_total 15454
telemt_me_idle_close_by_peer_total 15451
telemt_me_route_drop_no_conn_total 245568
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 466721
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
telemt_me_writer_removed_unexpected_total 14684
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14379
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 441389
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 8158618904 (7.60 GB)
telemt_user_octets_to_client{user="hello"} 252571968160 (235.23 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 71
```