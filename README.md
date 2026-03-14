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

# Server Metrics 2026-03-14 04:50:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 163018.8 (45h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 631540
telemt_connections_bad_total 32274
telemt_handshake_timeouts_total 12967
telemt_upstream_connect_attempt_total 41679
telemt_upstream_connect_success_total 41466
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 41679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5560
telemt_me_reconnect_attempts_total 37621
telemt_me_reconnect_success_total 32937
telemt_me_reader_eof_total 35202
telemt_me_idle_close_by_peer_total 35201
telemt_me_route_drop_no_conn_total 205353
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 534262
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1872
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1242
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 780
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 33442
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32917
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 505
telemt_user_connections_total{user="hello"} 534147
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 15784573910 (14.70 GB)
telemt_user_octets_to_client{user="hello"} 258873521484 (241.09 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 162911.7 (45h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319103
telemt_connections_bad_total 2272
telemt_handshake_timeouts_total 2330
telemt_upstream_connect_attempt_total 147336
telemt_upstream_connect_success_total 146142
telemt_upstream_connect_fail_total 1194
telemt_upstream_connect_attempts_per_request{bucket="1"} 147336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1194
telemt_me_keepalive_timeout_total 3872
telemt_me_reconnect_attempts_total 171542
telemt_me_reconnect_success_total 34732
telemt_me_reader_eof_total 39918
telemt_me_idle_close_by_peer_total 39918
telemt_me_route_drop_no_conn_total 101443
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199107
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 39333
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 34715
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4601
telemt_user_connections_total{user="hello"} 302216
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 3145476671 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 97686962023 (90.98 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 162875.6 (45h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371400
telemt_connections_bad_total 2940
telemt_handshake_timeouts_total 34857
telemt_upstream_connect_attempt_total 43120
telemt_upstream_connect_success_total 43111
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3396
telemt_me_reconnect_attempts_total 36251
telemt_me_reconnect_success_total 34969
telemt_me_reader_eof_total 37590
telemt_me_idle_close_by_peer_total 37590
telemt_me_route_drop_no_conn_total 133236
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320747
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 35396
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34948
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 320527
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 12711042720 (11.84 GB)
telemt_user_octets_to_client{user="hello"} 128387252320 (119.57 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 162851.0 (45h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472885
telemt_connections_bad_total 15582
telemt_handshake_timeouts_total 4411
telemt_upstream_connect_attempt_total 72945
telemt_upstream_connect_success_total 62421
telemt_upstream_connect_fail_total 10524
telemt_upstream_connect_attempts_per_request{bucket="1"} 72945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24928
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10524
telemt_me_keepalive_timeout_total 5290
telemt_me_reconnect_attempts_total 141339
telemt_me_reconnect_success_total 35289
telemt_me_reader_eof_total 39704
telemt_me_idle_close_by_peer_total 39696
telemt_me_route_drop_no_conn_total 169653
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401493
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1712
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 1208
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 39009
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 35279
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3720
telemt_user_connections_total{user="hello"} 420343
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 9208527363 (8.58 GB)
telemt_user_octets_to_client{user="hello"} 164658613316 (153.35 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 113022.5 (31h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185447
telemt_connections_bad_total 26814
telemt_handshake_timeouts_total 1642
telemt_upstream_connect_attempt_total 40626
telemt_upstream_connect_success_total 40250
telemt_upstream_connect_fail_total 376
telemt_upstream_connect_attempts_per_request{bucket="1"} 40626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 376
telemt_me_keepalive_timeout_total 2397
telemt_me_reconnect_attempts_total 43154
telemt_me_reconnect_success_total 29732
telemt_me_reader_eof_total 31817
telemt_me_idle_close_by_peer_total 31817
telemt_me_route_drop_no_conn_total 54964
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147003
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 30417
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 29714
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 685
telemt_user_connections_total{user="hello"} 151756
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 2257178737 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 68967213391 (64.23 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 162807.0 (45h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 924556
telemt_connections_bad_total 28257
telemt_handshake_timeouts_total 25756
telemt_upstream_connect_attempt_total 33826
telemt_upstream_connect_success_total 33644
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 33826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 4581
telemt_me_reconnect_attempts_total 30275
telemt_me_reconnect_success_total 25604
telemt_me_reader_eof_total 27480
telemt_me_idle_close_by_peer_total 27477
telemt_me_route_drop_no_conn_total 439647
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 863175
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 26076
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25597
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 472
telemt_user_connections_total{user="hello"} 835837
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 14578171260 (13.58 GB)
telemt_user_octets_to_client{user="hello"} 423930881040 (394.82 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 34
```