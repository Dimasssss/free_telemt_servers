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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 11:56:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 50873.4 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1241131
telemt_connections_bad_total 103294
telemt_connections_current 1625
telemt_connections_me_current 1625
telemt_handshake_timeouts_total 43406
telemt_upstream_connect_attempt_total 9748
telemt_upstream_connect_success_total 9581
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 9748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 8907
telemt_me_reconnect_success_total 7019
telemt_me_reader_eof_total 7429
telemt_me_idle_close_by_peer_total 7426
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 513826
telemt_me_route_drop_channel_closed_total 203
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 973058
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5416
telemt_desync_full_logged_total 1657
telemt_desync_suppressed_total 3759
telemt_desync_frames_bucket_total{bucket="1_2"} 1740
telemt_desync_frames_bucket_total{bucket="3_10"} 1963
telemt_desync_frames_bucket_total{bucket="gt_10"} 1713
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 7179
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 6998
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 966971
telemt_user_connections_current{user="hello"} 1625
telemt_user_octets_from_client{user="hello"} 14954398696 (13.93 GB)
telemt_user_octets_to_client{user="hello"} 293170324968 (273.04 GB)
telemt_user_unique_ips_current{user="hello"} 571
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 50877.5 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3496909
telemt_connections_bad_total 228874
telemt_connections_current 4019
telemt_connections_me_current 4019
telemt_handshake_timeouts_total 62628
telemt_upstream_connect_attempt_total 9566
telemt_upstream_connect_success_total 9389
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 9566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16904
telemt_me_reconnect_success_total 6798
telemt_me_reader_eof_total 7430
telemt_me_idle_close_by_peer_total 7429
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 2928914
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2942023
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11376
telemt_desync_full_logged_total 3814
telemt_desync_suppressed_total 7562
telemt_desync_frames_bucket_total{bucket="1_2"} 2209
telemt_desync_frames_bucket_total{bucket="3_10"} 4479
telemt_desync_frames_bucket_total{bucket="gt_10"} 4688
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7233
telemt_me_refill_failed_total 315
telemt_me_writer_restored_same_endpoint_total 6775
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 2941644
telemt_user_connections_current{user="hello"} 4019
telemt_user_octets_from_client{user="hello"} 37431356924 (34.86 GB)
telemt_user_octets_to_client{user="hello"} 846174121804 (788.06 GB)
telemt_user_unique_ips_current{user="hello"} 1370
telemt_user_unique_ips_recent_window{user="hello"} 909
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 50875.0 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2622111
telemt_connections_bad_total 306332
telemt_connections_current 3389
telemt_connections_me_current 3389
telemt_handshake_timeouts_total 52591
telemt_upstream_connect_attempt_total 9217
telemt_upstream_connect_success_total 9217
telemt_upstream_connect_attempts_per_request{bucket="1"} 9217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4419
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 7817
telemt_me_reconnect_success_total 6622
telemt_me_reader_eof_total 7020
telemt_me_idle_close_by_peer_total 7019
telemt_me_route_drop_no_conn_total 1603502
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2066075
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8514
telemt_desync_full_logged_total 2704
telemt_desync_suppressed_total 5810
telemt_desync_frames_bucket_total{bucket="1_2"} 1929
telemt_desync_frames_bucket_total{bucket="3_10"} 3123
telemt_desync_frames_bucket_total{bucket="gt_10"} 3462
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6773
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6606
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 2063845
telemt_user_connections_current{user="hello"} 3389
telemt_user_octets_from_client{user="hello"} 28706859532 (26.74 GB)
telemt_user_octets_to_client{user="hello"} 877823325704 (817.54 GB)
telemt_user_unique_ips_current{user="hello"} 1142
telemt_user_unique_ips_recent_window{user="hello"} 579
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 50928.2 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2680972
telemt_connections_bad_total 140401
telemt_connections_current 3141
telemt_connections_me_current 3141
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 65597
telemt_upstream_connect_attempt_total 17537
telemt_upstream_connect_success_total 17356
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 17537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 10955
telemt_me_reconnect_success_total 6602
telemt_me_reader_eof_total 7027
telemt_me_idle_close_by_peer_total 7026
telemt_me_route_drop_no_conn_total 1748175
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2079976
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7409
telemt_desync_full_logged_total 2463
telemt_desync_suppressed_total 4946
telemt_desync_frames_bucket_total{bucket="1_2"} 1566
telemt_desync_frames_bucket_total{bucket="3_10"} 2907
telemt_desync_frames_bucket_total{bucket="gt_10"} 2936
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7076
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6578
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 474
telemt_user_connections_total{user="hello"} 2086071
telemt_user_connections_current{user="hello"} 3141
telemt_user_octets_from_client{user="hello"} 23328256352 (21.73 GB)
telemt_user_octets_to_client{user="hello"} 560360936090 (521.88 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1039
telemt_user_unique_ips_recent_window{user="hello"} 500
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 50871.6 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3140600
telemt_connections_bad_total 668363
telemt_connections_current 3222
telemt_connections_me_current 3222
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 63157
telemt_upstream_connect_attempt_total 20904
telemt_upstream_connect_success_total 18440
telemt_upstream_connect_fail_total 2464
telemt_upstream_connect_attempts_per_request{bucket="1"} 20904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 588
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2464
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 7736
telemt_me_reconnect_success_total 6480
telemt_me_reader_eof_total 6869
telemt_me_idle_close_by_peer_total 6866
telemt_me_route_drop_no_conn_total 1240550
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2087028
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8975
telemt_desync_full_logged_total 2803
telemt_desync_suppressed_total 6172
telemt_desync_frames_bucket_total{bucket="1_2"} 1686
telemt_desync_frames_bucket_total{bucket="3_10"} 3873
telemt_desync_frames_bucket_total{bucket="gt_10"} 3416
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 6629
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6456
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 76
telemt_me_async_recovery_trigger_total 1061
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 2095031
telemt_user_connections_current{user="hello"} 3222
telemt_user_octets_from_client{user="hello"} 35488158163 (33.05 GB)
telemt_user_octets_to_client{user="hello"} 825288259315 (768.61 GB)
telemt_user_msgs_from_client{user="hello"} 54060
telemt_user_msgs_to_client{user="hello"} 260638
telemt_user_unique_ips_current{user="hello"} 1153
telemt_user_unique_ips_recent_window{user="hello"} 687
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 50883.7 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 541935
telemt_connections_bad_total 18911
telemt_connections_current 1034
telemt_connections_me_current 1034
telemt_handshake_timeouts_total 4214
telemt_upstream_connect_attempt_total 12553
telemt_upstream_connect_success_total 12229
telemt_upstream_connect_fail_total 324
telemt_upstream_connect_attempts_per_request{bucket="1"} 12553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6213
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 324
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 17246
telemt_me_reconnect_success_total 9654
telemt_me_reader_eof_total 10292
telemt_me_idle_close_by_peer_total 10292
telemt_me_route_drop_no_conn_total 280700
telemt_me_route_drop_channel_closed_total 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492492
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1106
telemt_desync_full_logged_total 387
telemt_desync_suppressed_total 719
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 448
telemt_desync_frames_bucket_total{bucket="gt_10"} 435
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9983
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9623
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 492423
telemt_user_connections_current{user="hello"} 1034
telemt_user_octets_from_client{user="hello"} 7881768352 (7.34 GB)
telemt_user_octets_to_client{user="hello"} 179003009736 (166.71 GB)
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 50873.8 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2184103
telemt_connections_bad_total 178241
telemt_connections_current 3262
telemt_connections_me_current 3262
telemt_handshake_timeouts_total 73367
telemt_upstream_connect_attempt_total 10256
telemt_upstream_connect_success_total 10255
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 9030
telemt_me_reconnect_success_total 7658
telemt_me_reader_eof_total 8096
telemt_me_idle_close_by_peer_total 8095
telemt_me_route_drop_no_conn_total 1092583
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1829029
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9975
telemt_desync_full_logged_total 3209
telemt_desync_suppressed_total 6766
telemt_desync_frames_bucket_total{bucket="1_2"} 1906
telemt_desync_frames_bucket_total{bucket="3_10"} 3785
telemt_desync_frames_bucket_total{bucket="gt_10"} 4284
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7800
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7643
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 1827811
telemt_user_connections_current{user="hello"} 3262
telemt_user_octets_from_client{user="hello"} 24070305348 (22.42 GB)
telemt_user_octets_to_client{user="hello"} 813794693344 (757.91 GB)
telemt_user_unique_ips_current{user="hello"} 1046
telemt_user_unique_ips_recent_window{user="hello"} 462
```