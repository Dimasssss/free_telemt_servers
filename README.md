# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-19 15:36:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 5521.0 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194428
telemt_connections_bad_total 5237
telemt_connections_current 1724
telemt_connections_direct_current 1724
telemt_relay_adaptive_promotions_total 53
telemt_relay_adaptive_demotions_total 16327
telemt_relay_adaptive_hard_promotions_total 52
telemt_handshake_timeouts_total 2101
telemt_upstream_connect_attempt_total 165379
telemt_upstream_connect_success_total 165292
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 165379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 158263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 165290
telemt_user_connections_current{user="hello"} 1723
telemt_user_octets_from_client{user="hello"} 2834621719 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 35809440716 (33.35 GB)
telemt_user_msgs_from_client{user="hello"} 3061678
telemt_user_msgs_to_client{user="hello"} 3589912
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 10395.8 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1123373
telemt_connections_bad_total 40294
telemt_connections_current 3807
telemt_connections_me_current 3807
telemt_handshake_timeouts_total 23139
telemt_upstream_connect_attempt_total 3170
telemt_upstream_connect_success_total 3141
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 3170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 5563
telemt_me_reconnect_success_total 1346
telemt_me_reader_eof_total 1467
telemt_me_idle_close_by_peer_total 1467
telemt_me_route_drop_no_conn_total 762585
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 930938
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3594
telemt_desync_full_logged_total 1119
telemt_desync_suppressed_total 2475
telemt_desync_frames_bucket_total{bucket="1_2"} 687
telemt_desync_frames_bucket_total{bucket="3_10"} 1407
telemt_desync_frames_bucket_total{bucket="gt_10"} 1500
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 1472
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1291
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 931184
telemt_user_connections_current{user="hello"} 3807
telemt_user_octets_from_client{user="hello"} 11789311082 (10.98 GB)
telemt_user_octets_to_client{user="hello"} 266912676750 (248.58 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1340
telemt_user_unique_ips_recent_window{user="hello"} 597
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 10374.3 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1038402
telemt_connections_bad_total 122131
telemt_connections_current 3082
telemt_connections_me_current 3082
telemt_handshake_timeouts_total 9875
telemt_upstream_connect_attempt_total 1770
telemt_upstream_connect_success_total 1755
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 1770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2098
telemt_me_reconnect_success_total 1188
telemt_me_reader_eof_total 1166
telemt_me_idle_close_by_peer_total 1165
telemt_me_route_drop_no_conn_total 883042
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 786757
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2780
telemt_desync_full_logged_total 754
telemt_desync_suppressed_total 2026
telemt_desync_frames_bucket_total{bucket="1_2"} 754
telemt_desync_frames_bucket_total{bucket="3_10"} 1036
telemt_desync_frames_bucket_total{bucket="gt_10"} 990
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 1159
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1187
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 783975
telemt_user_connections_current{user="hello"} 3082
telemt_user_octets_from_client{user="hello"} 8694589984 (8.10 GB)
telemt_user_octets_to_client{user="hello"} 219430530924 (204.36 GB)
telemt_user_unique_ips_current{user="hello"} 1036
telemt_user_unique_ips_recent_window{user="hello"} 457
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 10361.8 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 840574
telemt_connections_bad_total 49335
telemt_connections_current 3142
telemt_connections_me_current 3142
telemt_handshake_timeouts_total 12477
telemt_upstream_connect_attempt_total 10847
telemt_upstream_connect_success_total 10331
telemt_upstream_connect_fail_total 516
telemt_upstream_connect_attempts_per_request{bucket="1"} 10847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 516
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 1626
telemt_me_reconnect_success_total 1307
telemt_me_reader_eof_total 1301
telemt_me_idle_close_by_peer_total 1300
telemt_me_route_drop_no_conn_total 551376
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 707400
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3194
telemt_desync_full_logged_total 1039
telemt_desync_suppressed_total 2155
telemt_desync_frames_bucket_total{bucket="1_2"} 694
telemt_desync_frames_bucket_total{bucket="3_10"} 1226
telemt_desync_frames_bucket_total{bucket="gt_10"} 1274
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 78
telemt_me_writer_removed_unexpected_total 1438
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 1303
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 715326
telemt_user_connections_current{user="hello"} 3142
telemt_user_octets_from_client{user="hello"} 14068287307 (13.10 GB)
telemt_user_octets_to_client{user="hello"} 168987360832 (157.38 GB)
telemt_user_msgs_from_client{user="hello"} 16739
telemt_user_msgs_to_client{user="hello"} 18599
telemt_user_unique_ips_current{user="hello"} 1037
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 64085.0 (17h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4539574
telemt_connections_bad_total 818529
telemt_connections_current 3521
telemt_connections_me_current 3521
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 87641
telemt_upstream_connect_attempt_total 63320
telemt_upstream_connect_success_total 60831
telemt_upstream_connect_fail_total 2489
telemt_upstream_connect_attempts_per_request{bucket="1"} 63320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1025
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2489
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 73813
telemt_me_reconnect_success_total 8415
telemt_me_reader_eof_total 8855
telemt_me_idle_close_by_peer_total 8852
telemt_me_route_drop_no_conn_total 2151076
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3129402
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13550
telemt_desync_full_logged_total 4137
telemt_desync_suppressed_total 9413
telemt_desync_frames_bucket_total{bucket="1_2"} 2275
telemt_desync_frames_bucket_total{bucket="3_10"} 5826
telemt_desync_frames_bucket_total{bucket="gt_10"} 5449
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8634
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 8391
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 3177805
telemt_user_connections_current{user="hello"} 3521
telemt_user_octets_from_client{user="hello"} 50113705127 (46.67 GB)
telemt_user_octets_to_client{user="hello"} 1129495526236 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1152
telemt_user_unique_ips_recent_window{user="hello"} 520
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 10326.2 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234957
telemt_connections_bad_total 19625
telemt_connections_current 991
telemt_connections_me_current 991
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 6470
telemt_upstream_connect_attempt_total 4639
telemt_upstream_connect_success_total 4502
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 4639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2680
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1430
telemt_me_reconnect_success_total 1399
telemt_me_reader_eof_total 1400
telemt_me_idle_close_by_peer_total 1400
telemt_me_route_drop_no_conn_total 142497
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194948
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 577
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 392
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 266
telemt_pool_swap_total 7
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 1374
telemt_me_writer_restored_same_endpoint_total 1390
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 197559
telemt_user_connections_current{user="hello"} 991
telemt_user_octets_from_client{user="hello"} 2705305048 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 51355410406 (47.83 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 10326.3 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 701730
telemt_connections_bad_total 47942
telemt_connections_current 3174
telemt_connections_me_current 3174
telemt_handshake_timeouts_total 11836
telemt_upstream_connect_attempt_total 1726
telemt_upstream_connect_success_total 1712
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 764
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1156
telemt_me_reconnect_success_total 1138
telemt_me_reader_eof_total 1182
telemt_me_idle_close_by_peer_total 1182
telemt_me_route_drop_no_conn_total 246062
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 602900
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3355
telemt_desync_full_logged_total 1016
telemt_desync_suppressed_total 2339
telemt_desync_frames_bucket_total{bucket="1_2"} 663
telemt_desync_frames_bucket_total{bucket="3_10"} 1139
telemt_desync_frames_bucket_total{bucket="gt_10"} 1553
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 1166
telemt_me_writer_restored_same_endpoint_total 1121
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 602493
telemt_user_connections_current{user="hello"} 3174
telemt_user_octets_from_client{user="hello"} 8864094684 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 258912813524 (241.13 GB)
telemt_user_unique_ips_current{user="hello"} 1055
telemt_user_unique_ips_recent_window{user="hello"} 441
```