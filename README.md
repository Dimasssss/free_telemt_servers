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

# Server Metrics 2026-03-19 03:14:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 19577.4 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243063
telemt_connections_bad_total 28732
telemt_connections_current 717
telemt_connections_me_current 717
telemt_handshake_timeouts_total 15193
telemt_upstream_connect_attempt_total 3862
telemt_upstream_connect_success_total 3801
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 3861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2836
telemt_me_reconnect_success_total 2821
telemt_me_reader_eof_total 2957
telemt_me_idle_close_by_peer_total 2957
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 65179
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187701
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1285
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 944
telemt_desync_frames_bucket_total{bucket="1_2"} 475
telemt_desync_frames_bucket_total{bucket="3_10"} 550
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2838
telemt_me_writer_restored_same_endpoint_total 2805
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 184926
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 1959430364 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 56854291244 (52.95 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 19581.3 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444698
telemt_connections_bad_total 37317
telemt_connections_current 1790
telemt_connections_me_current 1790
telemt_handshake_timeouts_total 10628
telemt_upstream_connect_attempt_total 3754
telemt_upstream_connect_success_total 3691
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 3754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_reconnect_attempts_total 2714
telemt_me_reconnect_success_total 2702
telemt_me_reader_eof_total 2843
telemt_me_idle_close_by_peer_total 2843
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 132928
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 369394
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1382
telemt_desync_full_logged_total 476
telemt_desync_suppressed_total 906
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 518
telemt_desync_frames_bucket_total{bucket="gt_10"} 550
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2743
telemt_me_writer_restored_same_endpoint_total 2686
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 369369
telemt_user_connections_current{user="hello"} 1790
telemt_user_octets_from_client{user="hello"} 12316499312 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 149070556604 (138.83 GB)
telemt_user_unique_ips_current{user="hello"} 710
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 19578.7 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364741
telemt_connections_bad_total 78625
telemt_connections_current 1338
telemt_connections_me_current 1338
telemt_handshake_timeouts_total 8759
telemt_upstream_connect_attempt_total 3707
telemt_upstream_connect_success_total 3707
telemt_upstream_connect_attempts_per_request{bucket="1"} 3707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 2731
telemt_me_reconnect_success_total 2721
telemt_me_reader_eof_total 2877
telemt_me_idle_close_by_peer_total 2877
telemt_me_route_drop_no_conn_total 104288
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266783
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1309
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 812
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 535
telemt_desync_frames_bucket_total{bucket="gt_10"} 548
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2762
telemt_me_writer_restored_same_endpoint_total 2705
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 266775
telemt_user_connections_current{user="hello"} 1338
telemt_user_octets_from_client{user="hello"} 5758213020 (5.36 GB)
telemt_user_octets_to_client{user="hello"} 162144825952 (151.01 GB)
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 19632.0 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429145
telemt_connections_bad_total 42190
telemt_connections_current 1225
telemt_connections_me_current 1225
telemt_handshake_timeouts_total 7503
telemt_upstream_connect_attempt_total 3585
telemt_upstream_connect_success_total 3585
telemt_upstream_connect_attempts_per_request{bucket="1"} 3585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2612
telemt_me_reconnect_success_total 2601
telemt_me_reader_eof_total 2736
telemt_me_idle_close_by_peer_total 2735
telemt_me_route_drop_no_conn_total 115072
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267100
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 670
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 421
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2631
telemt_me_writer_restored_same_endpoint_total 2577
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 266834
telemt_user_connections_current{user="hello"} 1225
telemt_user_octets_from_client{user="hello"} 2363829792 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 93375954836 (86.96 GB)
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 19575.3 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385629
telemt_connections_bad_total 28796
telemt_connections_current 1540
telemt_connections_me_current 1540
telemt_handshake_timeouts_total 13832
telemt_upstream_connect_attempt_total 3735
telemt_upstream_connect_success_total 3714
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 2739
telemt_me_reconnect_success_total 2724
telemt_me_reader_eof_total 2868
telemt_me_idle_close_by_peer_total 2868
telemt_me_route_drop_no_conn_total 114331
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289437
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1313
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 443
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2742
telemt_me_writer_restored_same_endpoint_total 2700
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 289357
telemt_user_connections_current{user="hello"} 1540
telemt_user_octets_from_client{user="hello"} 10123192940 (9.43 GB)
telemt_user_octets_to_client{user="hello"} 165151771484 (153.81 GB)
telemt_user_unique_ips_current{user="hello"} 615
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 19586.7 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92475
telemt_connections_bad_total 9905
telemt_connections_current 310
telemt_connections_me_current 310
telemt_handshake_timeouts_total 409
telemt_upstream_connect_attempt_total 5576
telemt_upstream_connect_success_total 5419
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 5576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2835
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_reconnect_attempts_total 6274
telemt_me_reconnect_success_total 4437
telemt_me_reader_eof_total 4656
telemt_me_idle_close_by_peer_total 4656
telemt_me_route_drop_no_conn_total 37374
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79128
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4501
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4407
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 79122
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 1621920092 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 54964689280 (51.19 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 19577.5 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270993
telemt_connections_bad_total 28040
telemt_connections_current 1325
telemt_connections_me_current 1325
telemt_handshake_timeouts_total 13738
telemt_upstream_connect_attempt_total 4175
telemt_upstream_connect_success_total 4175
telemt_upstream_connect_attempts_per_request{bucket="1"} 4175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3201
telemt_me_reconnect_success_total 3192
telemt_me_reader_eof_total 3363
telemt_me_idle_close_by_peer_total 3363
telemt_me_route_drop_no_conn_total 78044
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222482
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1145
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 698
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 477
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3228
telemt_me_writer_restored_same_endpoint_total 3177
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 222503
telemt_user_connections_current{user="hello"} 1325
telemt_user_octets_from_client{user="hello"} 2376528560 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 117575475520 (109.50 GB)
telemt_user_unique_ips_current{user="hello"} 504
telemt_user_unique_ips_recent_window{user="hello"} 125
```