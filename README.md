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

# Server Metrics 2026-03-19 17:51:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 2046.7 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67071
telemt_connections_bad_total 1875
telemt_connections_current 1539
telemt_connections_me_current 1539
telemt_handshake_timeouts_total 672
telemt_upstream_connect_attempt_total 343
telemt_upstream_connect_success_total 337
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 184
telemt_me_reconnect_success_total 183
telemt_me_reader_eof_total 172
telemt_me_idle_close_by_peer_total 172
telemt_me_route_drop_no_conn_total 22732
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58663
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 266
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 190
telemt_me_writer_restored_same_endpoint_total 170
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 58752
telemt_user_connections_current{user="hello"} 1539
telemt_user_octets_from_client{user="hello"} 1019205908 (971.99 MB)
telemt_user_octets_to_client{user="hello"} 21049486840 (19.60 GB)
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 18502.2 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1868793
telemt_connections_bad_total 93810
telemt_connections_current 3796
telemt_connections_me_current 3796
telemt_handshake_timeouts_total 34990
telemt_upstream_connect_attempt_total 4383
telemt_upstream_connect_success_total 4329
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 4383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6360
telemt_me_reconnect_success_total 2137
telemt_me_reader_eof_total 2312
telemt_me_idle_close_by_peer_total 2312
telemt_me_route_drop_no_conn_total 1094596
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1546016
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6080
telemt_desync_full_logged_total 1901
telemt_desync_suppressed_total 4179
telemt_desync_frames_bucket_total{bucket="1_2"} 1189
telemt_desync_frames_bucket_total{bucket="3_10"} 2411
telemt_desync_frames_bucket_total{bucket="gt_10"} 2480
telemt_pool_swap_total 12
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2281
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2082
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 1546009
telemt_user_connections_current{user="hello"} 3796
telemt_user_octets_from_client{user="hello"} 22911009390 (21.34 GB)
telemt_user_octets_to_client{user="hello"} 492889477910 (459.04 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1308
telemt_user_unique_ips_recent_window{user="hello"} 534
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 18480.6 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1731476
telemt_connections_bad_total 209188
telemt_connections_current 2767
telemt_connections_me_current 2767
telemt_handshake_timeouts_total 18352
telemt_upstream_connect_attempt_total 2962
telemt_upstream_connect_success_total 2943
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2896
telemt_me_reconnect_success_total 1978
telemt_me_reader_eof_total 2005
telemt_me_idle_close_by_peer_total 2004
telemt_me_route_drop_no_conn_total 1548799
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1313512
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4094
telemt_desync_full_logged_total 1219
telemt_desync_suppressed_total 2875
telemt_desync_frames_bucket_total{bucket="1_2"} 1073
telemt_desync_frames_bucket_total{bucket="3_10"} 1535
telemt_desync_frames_bucket_total{bucket="gt_10"} 1486
telemt_pool_swap_total 14
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 1965
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1977
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1310567
telemt_user_connections_current{user="hello"} 2767
telemt_user_octets_from_client{user="hello"} 16609410880 (15.47 GB)
telemt_user_octets_to_client{user="hello"} 399981279148 (372.51 GB)
telemt_user_unique_ips_current{user="hello"} 970
telemt_user_unique_ips_recent_window{user="hello"} 373
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 18468.3 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1576293
telemt_connections_bad_total 58582
telemt_connections_current 2811
telemt_connections_me_current 2811
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 21997
telemt_upstream_connect_attempt_total 20191
telemt_upstream_connect_success_total 19260
telemt_upstream_connect_fail_total 931
telemt_upstream_connect_attempts_per_request{bucket="1"} 20191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3156
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 337
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 931
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4632
telemt_me_reconnect_success_total 2358
telemt_me_reader_eof_total 2445
telemt_me_idle_close_by_peer_total 2444
telemt_me_route_drop_no_conn_total 1377154
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1360451
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5425
telemt_desync_full_logged_total 1705
telemt_desync_suppressed_total 3720
telemt_desync_frames_bucket_total{bucket="1_2"} 1425
telemt_desync_frames_bucket_total{bucket="3_10"} 1997
telemt_desync_frames_bucket_total{bucket="gt_10"} 2003
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_removed_unexpected_total 2691
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2354
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 1375743
telemt_user_connections_current{user="hello"} 2811
telemt_user_octets_from_client{user="hello"} 25508159045 (23.76 GB)
telemt_user_octets_to_client{user="hello"} 299246381310 (278.69 GB)
telemt_user_msgs_from_client{user="hello"} 40382
telemt_user_msgs_to_client{user="hello"} 85113
telemt_user_unique_ips_current{user="hello"} 974
telemt_user_unique_ips_recent_window{user="hello"} 424
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 72191.6 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5214628
telemt_connections_bad_total 919516
telemt_connections_current 3266
telemt_connections_me_current 3266
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 97136
telemt_upstream_connect_attempt_total 64601
telemt_upstream_connect_success_total 62110
telemt_upstream_connect_fail_total 2491
telemt_upstream_connect_attempts_per_request{bucket="1"} 64601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1041
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74702
telemt_me_reconnect_success_total 9296
telemt_me_reader_eof_total 9794
telemt_me_idle_close_by_peer_total 9791
telemt_me_route_drop_no_conn_total 2440655
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3648082
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
telemt_desync_total 15940
telemt_desync_full_logged_total 4854
telemt_desync_suppressed_total 11086
telemt_desync_frames_bucket_total{bucket="1_2"} 2615
telemt_desync_frames_bucket_total{bucket="3_10"} 6671
telemt_desync_frames_bucket_total{bucket="gt_10"} 6654
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 9534
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9272
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 3696205
telemt_user_connections_current{user="hello"} 3266
telemt_user_octets_from_client{user="hello"} 57649041823 (53.69 GB)
telemt_user_octets_to_client{user="hello"} 1351047626500 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1137
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 18442.3 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402839
telemt_connections_bad_total 29527
telemt_connections_current 1273
telemt_connections_me_current 1273
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 8331
telemt_upstream_connect_attempt_total 6229
telemt_upstream_connect_success_total 6090
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 6229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 2626
telemt_me_reconnect_success_total 2584
telemt_me_reader_eof_total 2641
telemt_me_idle_close_by_peer_total 2641
telemt_me_route_drop_no_conn_total 236878
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329398
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 971
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 672
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 393
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 11
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 83
telemt_me_writer_removed_unexpected_total 2583
telemt_me_writer_restored_same_endpoint_total 2575
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 338735
telemt_user_connections_current{user="hello"} 1273
telemt_user_octets_from_client{user="hello"} 4366892012 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 81193896098 (75.62 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 18432.7 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1232077
telemt_connections_bad_total 83398
telemt_connections_current 3117
telemt_connections_me_current 3117
telemt_handshake_timeouts_total 21228
telemt_upstream_connect_attempt_total 3108
telemt_upstream_connect_success_total 3085
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 3108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 2139
telemt_me_reconnect_success_total 2114
telemt_me_reader_eof_total 2211
telemt_me_idle_close_by_peer_total 2211
telemt_me_route_drop_no_conn_total 479564
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1058330
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5839
telemt_desync_full_logged_total 1767
telemt_desync_suppressed_total 4072
telemt_desync_frames_bucket_total{bucket="1_2"} 1157
telemt_desync_frames_bucket_total{bucket="3_10"} 2019
telemt_desync_frames_bucket_total{bucket="gt_10"} 2663
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 2155
telemt_me_writer_restored_same_endpoint_total 2097
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1057844
telemt_user_connections_current{user="hello"} 3117
telemt_user_octets_from_client{user="hello"} 16169662624 (15.06 GB)
telemt_user_octets_to_client{user="hello"} 460400873060 (428.78 GB)
telemt_user_unique_ips_current{user="hello"} 1017
telemt_user_unique_ips_recent_window{user="hello"} 391
```