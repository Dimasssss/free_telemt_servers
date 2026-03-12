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

# Server Metrics 2026-03-12 22:05:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 52327.6 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242582
telemt_connections_bad_total 2686
telemt_handshake_timeouts_total 5190
telemt_upstream_connect_attempt_total 13141
telemt_upstream_connect_success_total 13080
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 13141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1466
telemt_me_reconnect_attempts_total 13868
telemt_me_reconnect_success_total 10400
telemt_me_reader_eof_total 11067
telemt_me_idle_close_by_peer_total 11066
telemt_me_route_drop_no_conn_total 74436
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199474
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 676
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 10627
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 10384
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 199241
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 3726816800 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 97393802704 (90.71 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 52220.3 (14h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108331
telemt_connections_bad_total 553
telemt_handshake_timeouts_total 806
telemt_upstream_connect_attempt_total 31070
telemt_upstream_connect_success_total 30732
telemt_upstream_connect_fail_total 338
telemt_upstream_connect_attempts_per_request{bucket="1"} 31070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 498
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 338
telemt_me_keepalive_timeout_total 378
telemt_me_reconnect_attempts_total 52262
telemt_me_reconnect_success_total 11613
telemt_me_reader_eof_total 13150
telemt_me_idle_close_by_peer_total 13150
telemt_me_route_drop_no_conn_total 39170
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86560
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 13
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
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 12968
telemt_me_refill_failed_total 1269
telemt_me_writer_restored_same_endpoint_total 11598
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1355
telemt_user_connections_total{user="hello"} 103061
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 1142651036 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 32857789299 (30.60 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 52183.7 (14h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134699
telemt_connections_bad_total 1581
telemt_handshake_timeouts_total 2216
telemt_upstream_connect_attempt_total 14357
telemt_upstream_connect_success_total 14356
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7571
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 12838
telemt_me_reconnect_success_total 11696
telemt_me_reader_eof_total 12457
telemt_me_idle_close_by_peer_total 12457
telemt_me_route_drop_no_conn_total 50738
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125797
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 11842
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 11676
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 125763
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 2558707304 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 59901237532 (55.79 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 52159.6 (14h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196274
telemt_connections_bad_total 13193
telemt_handshake_timeouts_total 1368
telemt_upstream_connect_attempt_total 25554
telemt_upstream_connect_success_total 15875
telemt_upstream_connect_fail_total 9679
telemt_upstream_connect_attempts_per_request{bucket="1"} 25554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7168
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9679
telemt_me_keepalive_timeout_total 2470
telemt_me_reconnect_attempts_total 42633
telemt_me_reconnect_success_total 10388
telemt_me_reader_eof_total 11743
telemt_me_idle_close_by_peer_total 11736
telemt_me_route_drop_no_conn_total 68742
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160478
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 11561
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 10378
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1173
telemt_user_connections_total{user="hello"} 163232
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 2956219746 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 67021494201 (62.42 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2331.2 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2410
telemt_connections_bad_total 418
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 594
telemt_upstream_connect_success_total 588
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 434
telemt_me_reconnect_success_total 433
telemt_me_reader_eof_total 434
telemt_me_idle_close_by_peer_total 434
telemt_me_route_drop_no_conn_total 709
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1858
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 432
telemt_me_writer_restored_same_endpoint_total 417
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 1858
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 6181820 (5.90 MB)
telemt_user_octets_to_client{user="hello"} 1044757672 (996.36 MB)
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 52116.0 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317814
telemt_connections_bad_total 4540
telemt_handshake_timeouts_total 2471
telemt_upstream_connect_attempt_total 10849
telemt_upstream_connect_success_total 10792
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 10849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 499
telemt_me_reconnect_attempts_total 11797
telemt_me_reconnect_success_total 8188
telemt_me_reader_eof_total 8745
telemt_me_idle_close_by_peer_total 8744
telemt_me_route_drop_no_conn_total 144417
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313014
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8402
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 8181
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 301316
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 5356874744 (4.99 GB)
telemt_user_octets_to_client{user="hello"} 152154029216 (141.70 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 30
```