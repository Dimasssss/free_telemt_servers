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

# Server Metrics 2026-03-19 15:31:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 5210.8 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179181
telemt_connections_bad_total 4891
telemt_connections_current 1686
telemt_connections_direct_current 1686
telemt_relay_adaptive_promotions_total 53
telemt_relay_adaptive_demotions_total 15268
telemt_relay_adaptive_hard_promotions_total 52
telemt_handshake_timeouts_total 1921
telemt_upstream_connect_attempt_total 153658
telemt_upstream_connect_success_total 153579
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 153658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 146950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 153577
telemt_user_connections_current{user="hello"} 1686
telemt_user_octets_from_client{user="hello"} 2718067283 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 33530310256 (31.23 GB)
telemt_user_msgs_from_client{user="hello"} 2903335
telemt_user_msgs_to_client{user="hello"} 3386991
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 10086.0 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1091285
telemt_connections_bad_total 39160
telemt_connections_current 3952
telemt_connections_me_current 3952
telemt_handshake_timeouts_total 22618
telemt_upstream_connect_attempt_total 3139
telemt_upstream_connect_success_total 3110
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 3139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 5532
telemt_me_reconnect_success_total 1315
telemt_me_reader_eof_total 1433
telemt_me_idle_close_by_peer_total 1433
telemt_me_route_drop_no_conn_total 750360
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 907878
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3471
telemt_desync_full_logged_total 1086
telemt_desync_suppressed_total 2385
telemt_desync_frames_bucket_total{bucket="1_2"} 657
telemt_desync_frames_bucket_total{bucket="3_10"} 1359
telemt_desync_frames_bucket_total{bucket="gt_10"} 1455
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 1440
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1260
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 908132
telemt_user_connections_current{user="hello"} 3952
telemt_user_octets_from_client{user="hello"} 11447527990 (10.66 GB)
telemt_user_octets_to_client{user="hello"} 258069096138 (240.35 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1342
telemt_user_unique_ips_recent_window{user="hello"} 628
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 10064.2 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1011663
telemt_connections_bad_total 117084
telemt_connections_current 3023
telemt_connections_me_current 3023
telemt_handshake_timeouts_total 9522
telemt_upstream_connect_attempt_total 1735
telemt_upstream_connect_success_total 1720
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 1735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2063
telemt_me_reconnect_success_total 1153
telemt_me_reader_eof_total 1129
telemt_me_idle_close_by_peer_total 1128
telemt_me_route_drop_no_conn_total 875257
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 768189
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2671
telemt_desync_full_logged_total 729
telemt_desync_suppressed_total 1942
telemt_desync_frames_bucket_total{bucket="1_2"} 724
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 941
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 1124
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1152
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 765399
telemt_user_connections_current{user="hello"} 3023
telemt_user_octets_from_client{user="hello"} 8391701984 (7.82 GB)
telemt_user_octets_to_client{user="hello"} 213581200472 (198.91 GB)
telemt_user_unique_ips_current{user="hello"} 1052
telemt_user_unique_ips_recent_window{user="hello"} 499
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 10052.0 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 818297
telemt_connections_bad_total 49006
telemt_connections_current 3159
telemt_connections_me_current 3159
telemt_handshake_timeouts_total 12329
telemt_upstream_connect_attempt_total 10772
telemt_upstream_connect_success_total 10259
telemt_upstream_connect_fail_total 513
telemt_upstream_connect_attempts_per_request{bucket="1"} 10772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1881
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 513
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 1551
telemt_me_reconnect_success_total 1235
telemt_me_reader_eof_total 1227
telemt_me_idle_close_by_peer_total 1226
telemt_me_route_drop_no_conn_total 537099
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 687374
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3044
telemt_desync_full_logged_total 1009
telemt_desync_suppressed_total 2035
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 1172
telemt_desync_frames_bucket_total{bucket="gt_10"} 1240
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 78
telemt_me_writer_removed_unexpected_total 1363
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 1231
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 695303
telemt_user_connections_current{user="hello"} 3159
telemt_user_octets_from_client{user="hello"} 13843379883 (12.89 GB)
telemt_user_octets_to_client{user="hello"} 163304470892 (152.09 GB)
telemt_user_msgs_from_client{user="hello"} 16739
telemt_user_msgs_to_client{user="hello"} 18599
telemt_user_unique_ips_current{user="hello"} 1048
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 63774.9 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4515712
telemt_connections_bad_total 817604
telemt_connections_current 3488
telemt_connections_me_current 3488
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 87206
telemt_upstream_connect_attempt_total 63230
telemt_upstream_connect_success_total 60743
telemt_upstream_connect_fail_total 2487
telemt_upstream_connect_attempts_per_request{bucket="1"} 63230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1024
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2487
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 73771
telemt_me_reconnect_success_total 8373
telemt_me_reader_eof_total 8814
telemt_me_idle_close_by_peer_total 8811
telemt_me_route_drop_no_conn_total 2142393
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3110136
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
telemt_desync_total 13411
telemt_desync_full_logged_total 4107
telemt_desync_suppressed_total 9304
telemt_desync_frames_bucket_total{bucket="1_2"} 2266
telemt_desync_frames_bucket_total{bucket="3_10"} 5757
telemt_desync_frames_bucket_total{bucket="gt_10"} 5388
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8592
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 8349
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 3158536
telemt_user_connections_current{user="hello"} 3488
telemt_user_octets_from_client{user="hello"} 49855918939 (46.43 GB)
telemt_user_octets_to_client{user="hello"} 1121252274368 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1168
telemt_user_unique_ips_recent_window{user="hello"} 554
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 10019.8 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229080
telemt_connections_bad_total 19128
telemt_connections_current 1057
telemt_connections_me_current 1057
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 6430
telemt_upstream_connect_attempt_total 4595
telemt_upstream_connect_success_total 4458
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 4595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1386
telemt_me_reconnect_success_total 1354
telemt_me_reader_eof_total 1346
telemt_me_idle_close_by_peer_total 1346
telemt_me_route_drop_no_conn_total 139051
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189860
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
telemt_desync_total 573
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 389
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 7
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 1328
telemt_me_writer_restored_same_endpoint_total 1345
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 192472
telemt_user_connections_current{user="hello"} 1057
telemt_user_octets_from_client{user="hello"} 2650592196 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 50127481650 (46.68 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 10016.3 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681087
telemt_connections_bad_total 46388
telemt_connections_current 3290
telemt_connections_me_current 3290
telemt_handshake_timeouts_total 11578
telemt_upstream_connect_attempt_total 1676
telemt_upstream_connect_success_total 1662
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1106
telemt_me_reconnect_success_total 1087
telemt_me_reader_eof_total 1128
telemt_me_idle_close_by_peer_total 1128
telemt_me_route_drop_no_conn_total 239201
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585646
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3246
telemt_desync_full_logged_total 982
telemt_desync_suppressed_total 2264
telemt_desync_frames_bucket_total{bucket="1_2"} 642
telemt_desync_frames_bucket_total{bucket="3_10"} 1087
telemt_desync_frames_bucket_total{bucket="gt_10"} 1517
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 1116
telemt_me_writer_restored_same_endpoint_total 1070
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 585246
telemt_user_connections_current{user="hello"} 3290
telemt_user_octets_from_client{user="hello"} 8543272512 (7.96 GB)
telemt_user_octets_to_client{user="hello"} 250869378652 (233.64 GB)
telemt_user_unique_ips_current{user="hello"} 1060
telemt_user_unique_ips_recent_window{user="hello"} 490
```