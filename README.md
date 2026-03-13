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

# Server Metrics 2026-03-13 07:43:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 87020.4 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335100
telemt_connections_bad_total 3167
telemt_handshake_timeouts_total 7482
telemt_upstream_connect_attempt_total 21849
telemt_upstream_connect_success_total 21749
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 21849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1657
telemt_me_reconnect_attempts_total 20893
telemt_me_reconnect_success_total 17388
telemt_me_reader_eof_total 18598
telemt_me_idle_close_by_peer_total 18597
telemt_me_route_drop_no_conn_total 104771
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285017
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 953
telemt_desync_full_logged_total 351
telemt_desync_suppressed_total 602
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 17683
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17372
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 284715
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 4738538016 (4.41 GB)
telemt_user_octets_to_client{user="hello"} 132500383204 (123.40 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 86913.9 (24h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152519
telemt_connections_bad_total 1478
telemt_handshake_timeouts_total 1177
telemt_upstream_connect_attempt_total 44688
telemt_upstream_connect_success_total 44086
telemt_upstream_connect_fail_total 602
telemt_upstream_connect_attempts_per_request{bucket="1"} 44688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 511
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 602
telemt_me_keepalive_timeout_total 671
telemt_me_reconnect_attempts_total 75896
telemt_me_reconnect_success_total 23246
telemt_me_reader_eof_total 25582
telemt_me_idle_close_by_peer_total 25582
telemt_me_route_drop_no_conn_total 57291
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127627
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 18
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 25081
telemt_me_refill_failed_total 1643
telemt_me_writer_restored_same_endpoint_total 23231
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1835
telemt_user_connections_total{user="hello"} 144119
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 1488890660 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 46152504531 (42.98 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 86877.6 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184601
telemt_connections_bad_total 1973
telemt_handshake_timeouts_total 3082
telemt_upstream_connect_attempt_total 23626
telemt_upstream_connect_success_total 23624
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 567
telemt_me_reconnect_attempts_total 20420
telemt_me_reconnect_success_total 19243
telemt_me_reader_eof_total 20637
telemt_me_idle_close_by_peer_total 20637
telemt_me_route_drop_no_conn_total 71154
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172689
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
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 19453
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19223
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 172619
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 3818112772 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 74456580864 (69.34 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 86853.1 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266590
telemt_connections_bad_total 13617
telemt_handshake_timeouts_total 2017
telemt_upstream_connect_attempt_total 36317
telemt_upstream_connect_success_total 26366
telemt_upstream_connect_fail_total 9951
telemt_upstream_connect_attempts_per_request{bucket="1"} 36317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9951
telemt_me_keepalive_timeout_total 3367
telemt_me_reconnect_attempts_total 70707
telemt_me_reconnect_success_total 19164
telemt_me_reader_eof_total 21382
telemt_me_idle_close_by_peer_total 21375
telemt_me_route_drop_no_conn_total 96036
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225742
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 805
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 301
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 21020
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 19154
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1856
telemt_user_connections_total{user="hello"} 228470
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 5219960218 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 87221220145 (81.23 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 37024.8 (10h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45462
telemt_connections_bad_total 7589
telemt_handshake_timeouts_total 401
telemt_upstream_connect_attempt_total 12625
telemt_upstream_connect_success_total 12495
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 12625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 300
telemt_me_reconnect_attempts_total 11588
telemt_me_reconnect_success_total 10620
telemt_me_reader_eof_total 11312
telemt_me_idle_close_by_peer_total 11312
telemt_me_route_drop_no_conn_total 13104
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36215
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 10743
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 10602
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 36214
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 263393760 (251.19 MB)
telemt_user_octets_to_client{user="hello"} 11020721752 (10.26 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 86809.6 (24h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454356
telemt_connections_bad_total 11694
telemt_handshake_timeouts_total 3647
telemt_upstream_connect_attempt_total 18433
telemt_upstream_connect_success_total 18334
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 18433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 1522
telemt_me_reconnect_attempts_total 17655
telemt_me_reconnect_success_total 14014
telemt_me_reader_eof_total 15054
telemt_me_idle_close_by_peer_total 15051
telemt_me_route_drop_no_conn_total 212692
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440067
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 364
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 14305
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14007
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 423328
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 7839533864 (7.30 GB)
telemt_user_octets_to_client{user="hello"} 244812752840 (228.00 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 66
```