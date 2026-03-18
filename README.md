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

# Server Metrics 2026-03-18 16:04:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2319.2 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81008
telemt_connections_bad_total 9008
telemt_handshake_timeouts_total 3458
telemt_upstream_connect_attempt_total 330
telemt_upstream_connect_success_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 174
telemt_me_reconnect_success_total 173
telemt_me_reader_eof_total 162
telemt_me_idle_close_by_peer_total 162
telemt_me_route_drop_no_conn_total 43219
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63844
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 365
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 278
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 178
telemt_me_writer_restored_same_endpoint_total 162
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 63820
telemt_user_connections_current{user="hello"} 1580
telemt_user_octets_from_client{user="hello"} 964723952 (920.03 MB)
telemt_user_octets_to_client{user="hello"} 19734614364 (18.38 GB)
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 7147.4 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 769878
telemt_connections_bad_total 54208
telemt_connections_current 3823
telemt_connections_me_current 3823
telemt_handshake_timeouts_total 13691
telemt_upstream_connect_attempt_total 1246
telemt_upstream_connect_success_total 1238
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 863
telemt_me_reconnect_success_total 855
telemt_me_reader_eof_total 778
telemt_me_idle_close_by_peer_total 777
telemt_me_route_drop_no_conn_total 765682
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 665675
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1740
telemt_desync_full_logged_total 542
telemt_desync_suppressed_total 1198
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 704
telemt_desync_frames_bucket_total{bucket="gt_10"} 686
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 784
telemt_me_writer_restored_same_endpoint_total 853
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 664878
telemt_user_connections_current{user="hello"} 3823
telemt_user_octets_from_client{user="hello"} 6183293388 (5.76 GB)
telemt_user_octets_to_client{user="hello"} 181221969936 (168.78 GB)
telemt_user_unique_ips_current{user="hello"} 1231
telemt_user_unique_ips_recent_window{user="hello"} 768
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 7076.5 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512097
telemt_connections_bad_total 34520
telemt_connections_current 3022
telemt_connections_me_current 3022
telemt_handshake_timeouts_total 10434
telemt_upstream_connect_attempt_total 961
telemt_upstream_connect_success_total 956
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 585
telemt_me_reconnect_success_total 578
telemt_me_reader_eof_total 598
telemt_me_idle_close_by_peer_total 598
telemt_me_route_drop_no_conn_total 278739
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 432167
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1573
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 1120
telemt_desync_frames_bucket_total{bucket="1_2"} 366
telemt_desync_frames_bucket_total{bucket="3_10"} 593
telemt_desync_frames_bucket_total{bucket="gt_10"} 614
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 594
telemt_me_writer_restored_same_endpoint_total 561
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 431902
telemt_user_connections_current{user="hello"} 3022
telemt_user_octets_from_client{user="hello"} 8397264320 (7.82 GB)
telemt_user_octets_to_client{user="hello"} 163772696316 (152.53 GB)
telemt_user_unique_ips_current{user="hello"} 964
telemt_user_unique_ips_recent_window{user="hello"} 425
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 7790.3 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 693256
telemt_connections_bad_total 8840
telemt_connections_current 2491
telemt_connections_me_current 2491
telemt_handshake_timeouts_total 9379
telemt_upstream_connect_attempt_total 1289
telemt_upstream_connect_success_total 1278
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 855
telemt_me_reconnect_success_total 845
telemt_me_reader_eof_total 835
telemt_me_idle_close_by_peer_total 834
telemt_me_route_drop_no_conn_total 1124987
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 630576
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2393
telemt_desync_full_logged_total 597
telemt_desync_suppressed_total 1796
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 1102
telemt_desync_frames_bucket_total{bucket="gt_10"} 775
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 833
telemt_me_writer_restored_same_endpoint_total 834
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 630574
telemt_user_connections_current{user="hello"} 2491
telemt_user_octets_from_client{user="hello"} 4573805232 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 119441321964 (111.24 GB)
telemt_user_unique_ips_current{user="hello"} 837
telemt_user_unique_ips_recent_window{user="hello"} 486
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2305.3 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178313
telemt_connections_bad_total 32463
telemt_handshake_timeouts_total 2310
telemt_upstream_connect_attempt_total 394
telemt_upstream_connect_success_total 384
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 230
telemt_me_reconnect_success_total 227
telemt_me_reader_eof_total 195
telemt_me_idle_close_by_peer_total 195
telemt_me_route_drop_no_conn_total 71698
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130396
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 445
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 217
telemt_me_writer_restored_same_endpoint_total 201
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_user_connections_total{user="hello"} 130173
telemt_user_connections_current{user="hello"} 3211
telemt_user_octets_from_client{user="hello"} 2213490728 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 49946455196 (46.52 GB)
telemt_user_unique_ips_current{user="hello"} 1024
telemt_user_unique_ips_recent_window{user="hello"} 454
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 7241.3 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142602
telemt_connections_bad_total 5761
telemt_connections_current 948
telemt_connections_me_current 948
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1264
telemt_upstream_connect_attempt_total 5350
telemt_upstream_connect_success_total 5341
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 330588
telemt_me_reconnect_success_total 1131
telemt_me_reader_eof_total 1063
telemt_me_idle_close_by_peer_total 1063
telemt_me_route_drop_no_conn_total 79593
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125099
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 257
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1059
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1120
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 128843
telemt_user_connections_current{user="hello"} 948
telemt_user_octets_from_client{user="hello"} 1956148881 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 27330876513 (25.45 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 6309.6 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396630
telemt_connections_bad_total 15122
telemt_connections_current 2712
telemt_connections_me_current 2712
telemt_handshake_timeouts_total 4461
telemt_upstream_connect_attempt_total 1199
telemt_upstream_connect_success_total 1199
telemt_upstream_connect_attempts_per_request{bucket="1"} 1199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 15152
telemt_me_reconnect_success_total 860
telemt_me_reader_eof_total 765
telemt_me_idle_close_by_peer_total 765
telemt_me_route_drop_no_conn_total 262495
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342300
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 881
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 548
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 403
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 775
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 799
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 342591
telemt_user_connections_current{user="hello"} 2712
telemt_user_octets_from_client{user="hello"} 4859033928 (4.53 GB)
telemt_user_octets_to_client{user="hello"} 143126724184 (133.30 GB)
telemt_user_unique_ips_current{user="hello"} 833
telemt_user_unique_ips_recent_window{user="hello"} 404
```