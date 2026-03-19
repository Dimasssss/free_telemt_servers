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

# Server Metrics 2026-03-19 03:30:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 20496.3 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260586
telemt_connections_bad_total 30095
telemt_connections_current 717
telemt_connections_me_current 717
telemt_handshake_timeouts_total 17274
telemt_upstream_connect_attempt_total 4041
telemt_upstream_connect_success_total 3981
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 4041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2971
telemt_me_reconnect_success_total 2956
telemt_me_reader_eof_total 3097
telemt_me_idle_close_by_peer_total 3097
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 68311
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197173
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1389
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 1022
telemt_desync_frames_bucket_total{bucket="1_2"} 520
telemt_desync_frames_bucket_total{bucket="3_10"} 580
telemt_desync_frames_bucket_total{bucket="gt_10"} 289
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2974
telemt_me_writer_restored_same_endpoint_total 2939
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 194398
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 2078353476 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 58671808956 (54.64 GB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 20500.2 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469243
telemt_connections_bad_total 37781
telemt_connections_current 1898
telemt_connections_me_current 1898
telemt_handshake_timeouts_total 11974
telemt_upstream_connect_attempt_total 3907
telemt_upstream_connect_success_total 3841
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 3907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_reconnect_attempts_total 2820
telemt_me_reconnect_success_total 2807
telemt_me_reader_eof_total 2957
telemt_me_idle_close_by_peer_total 2957
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 140245
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390739
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1456
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 954
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 546
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2849
telemt_me_writer_restored_same_endpoint_total 2791
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 390712
telemt_user_connections_current{user="hello"} 1898
telemt_user_octets_from_client{user="hello"} 12501866852 (11.64 GB)
telemt_user_octets_to_client{user="hello"} 160816984740 (149.77 GB)
telemt_user_unique_ips_current{user="hello"} 724
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 20497.3 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385597
telemt_connections_bad_total 82356
telemt_connections_current 1426
telemt_connections_me_current 1426
telemt_handshake_timeouts_total 9437
telemt_upstream_connect_attempt_total 3867
telemt_upstream_connect_success_total 3867
telemt_upstream_connect_attempts_per_request{bucket="1"} 3867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 2847
telemt_me_reconnect_success_total 2837
telemt_me_reader_eof_total 3001
telemt_me_idle_close_by_peer_total 3001
telemt_me_route_drop_no_conn_total 114497
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282193
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1326
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 820
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 541
telemt_desync_frames_bucket_total{bucket="gt_10"} 558
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2882
telemt_me_writer_restored_same_endpoint_total 2821
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 282188
telemt_user_connections_current{user="hello"} 1426
telemt_user_octets_from_client{user="hello"} 6024667564 (5.61 GB)
telemt_user_octets_to_client{user="hello"} 174228582024 (162.26 GB)
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 20550.5 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462636
telemt_connections_bad_total 50254
telemt_connections_current 1252
telemt_connections_me_current 1252
telemt_handshake_timeouts_total 8541
telemt_upstream_connect_attempt_total 3743
telemt_upstream_connect_success_total 3743
telemt_upstream_connect_attempts_per_request{bucket="1"} 3743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2727
telemt_me_reconnect_success_total 2716
telemt_me_reader_eof_total 2860
telemt_me_idle_close_by_peer_total 2859
telemt_me_route_drop_no_conn_total 119507
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282646
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 772
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 495
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2748
telemt_me_writer_restored_same_endpoint_total 2692
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 282379
telemt_user_connections_current{user="hello"} 1252
telemt_user_octets_from_client{user="hello"} 2507539988 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 100587947356 (93.68 GB)
telemt_user_unique_ips_current{user="hello"} 502
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 20493.9 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433886
telemt_connections_bad_total 56678
telemt_connections_current 1588
telemt_connections_me_current 1588
telemt_handshake_timeouts_total 14776
telemt_upstream_connect_attempt_total 3894
telemt_upstream_connect_success_total 3871
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 3894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 2853
telemt_me_reconnect_success_total 2837
telemt_me_reader_eof_total 2992
telemt_me_idle_close_by_peer_total 2992
telemt_me_route_drop_no_conn_total 120704
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305742
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1363
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 840
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 542
telemt_desync_frames_bucket_total{bucket="gt_10"} 459
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2859
telemt_me_writer_restored_same_endpoint_total 2813
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 305662
telemt_user_connections_current{user="hello"} 1588
telemt_user_octets_from_client{user="hello"} 10379714368 (9.67 GB)
telemt_user_octets_to_client{user="hello"} 179585731532 (167.25 GB)
telemt_user_unique_ips_current{user="hello"} 651
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 20505.3 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96615
telemt_connections_bad_total 9940
telemt_connections_current 347
telemt_connections_me_current 347
telemt_handshake_timeouts_total 422
telemt_upstream_connect_attempt_total 5799
telemt_upstream_connect_success_total 5636
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 5799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2955
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_reconnect_attempts_total 6448
telemt_me_reconnect_success_total 4610
telemt_me_reader_eof_total 4839
telemt_me_idle_close_by_peer_total 4839
telemt_me_route_drop_no_conn_total 39913
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83034
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 4674
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4580
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 83028
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 1650067048 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 56289619472 (52.42 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 20496.3 (5h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288299
telemt_connections_bad_total 28951
telemt_connections_current 1359
telemt_connections_me_current 1359
telemt_handshake_timeouts_total 15377
telemt_upstream_connect_attempt_total 4367
telemt_upstream_connect_success_total 4367
telemt_upstream_connect_attempts_per_request{bucket="1"} 4367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3350
telemt_me_reconnect_success_total 3341
telemt_me_reader_eof_total 3519
telemt_me_idle_close_by_peer_total 3519
telemt_me_route_drop_no_conn_total 82521
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236748
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1229
telemt_desync_full_logged_total 472
telemt_desync_suppressed_total 757
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 483
telemt_desync_frames_bucket_total{bucket="gt_10"} 518
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3378
telemt_me_writer_restored_same_endpoint_total 3326
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 236770
telemt_user_connections_current{user="hello"} 1359
telemt_user_octets_from_client{user="hello"} 2569348260 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 126486870532 (117.80 GB)
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 133
```