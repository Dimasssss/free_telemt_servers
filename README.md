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

# Server Metrics 2026-03-16 18:02:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 15853.2 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159719
telemt_connections_bad_total 696
telemt_handshake_timeouts_total 4067
telemt_upstream_connect_attempt_total 3396
telemt_upstream_connect_success_total 3383
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3709
telemt_me_reconnect_success_total 2539
telemt_me_reader_eof_total 2638
telemt_me_idle_close_by_peer_total 2637
telemt_me_route_drop_no_conn_total 48667
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149704
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 745
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 571
telemt_desync_frames_bucket_total{bucket="1_2"} 280
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2593
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2537
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 149618
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 2799628076 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 85173320348 (79.32 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 10632.0 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75064
telemt_connections_bad_total 624
telemt_handshake_timeouts_total 3200
telemt_upstream_connect_attempt_total 2254
telemt_upstream_connect_success_total 2242
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 5179
telemt_me_reconnect_success_total 1671
telemt_me_reader_eof_total 1815
telemt_me_idle_close_by_peer_total 1815
telemt_me_route_drop_no_conn_total 43182
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68517
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1810
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1666
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 68458
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 808706612 (771.24 MB)
telemt_user_octets_to_client{user="hello"} 20033477444 (18.66 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 15966.4 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64599
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 878
telemt_upstream_connect_attempt_total 4738
telemt_upstream_connect_success_total 4691
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 4738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 41747
telemt_me_reconnect_success_total 2861
telemt_me_reader_eof_total 3212
telemt_me_idle_close_by_peer_total 3212
telemt_me_route_drop_no_conn_total 22542
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59610
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 162
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3196
telemt_me_refill_failed_total 1214
telemt_me_writer_restored_same_endpoint_total 2817
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 60544
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 814367562 (776.64 MB)
telemt_user_octets_to_client{user="hello"} 16952745062 (15.79 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 16102.7 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125411
telemt_connections_bad_total 226
telemt_handshake_timeouts_total 1765
telemt_upstream_connect_attempt_total 3443
telemt_upstream_connect_success_total 3417
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1756
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8896
telemt_me_reconnect_success_total 2539
telemt_me_reader_eof_total 2790
telemt_me_idle_close_by_peer_total 2789
telemt_me_route_drop_no_conn_total 45966
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119014
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 660
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 276
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2771
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2535
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 118983
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 1649222832 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 29777082984 (27.73 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 13563.1 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71790
telemt_connections_bad_total 20405
telemt_handshake_timeouts_total 572
telemt_upstream_connect_attempt_total 3546
telemt_upstream_connect_success_total 3492
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 3546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 4440
telemt_me_reconnect_success_total 2777
telemt_me_reader_eof_total 2864
telemt_me_idle_close_by_peer_total 2864
telemt_me_route_drop_no_conn_total 51198
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67173
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2930
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 2777
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 48216
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 2070302592 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 32941643188 (30.68 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 15677.1 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181294
telemt_connections_bad_total 2176
telemt_handshake_timeouts_total 3392
telemt_upstream_connect_attempt_total 3258
telemt_upstream_connect_success_total 3258
telemt_upstream_connect_attempts_per_request{bucket="1"} 3258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 7441
telemt_me_reconnect_success_total 2413
telemt_me_reader_eof_total 2627
telemt_me_idle_close_by_peer_total 2626
telemt_me_route_drop_no_conn_total 81848
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168349
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 89
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2590
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2407
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 168016
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 3213634896 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 64092977232 (59.69 GB)
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 80
```