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

# Server Metrics 2026-03-19 15:16:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 4291.4 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135273
telemt_connections_bad_total 4039
telemt_connections_current 1606
telemt_connections_direct_current 1606
telemt_relay_adaptive_promotions_total 50
telemt_relay_adaptive_demotions_total 12466
telemt_relay_adaptive_hard_promotions_total 49
telemt_handshake_timeouts_total 1560
telemt_upstream_connect_attempt_total 120840
telemt_upstream_connect_success_total 120778
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 120840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 120776
telemt_user_connections_current{user="hello"} 1606
telemt_user_octets_from_client{user="hello"} 2040591189 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 27493488558 (25.61 GB)
telemt_user_msgs_from_client{user="hello"} 2326519
telemt_user_msgs_to_client{user="hello"} 2789127
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 9166.2 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 995867
telemt_connections_bad_total 36784
telemt_connections_current 3855
telemt_connections_me_current 3855
telemt_handshake_timeouts_total 21027
telemt_upstream_connect_attempt_total 3022
telemt_upstream_connect_success_total 2995
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 3022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 5461
telemt_me_reconnect_success_total 1245
telemt_me_reader_eof_total 1356
telemt_me_idle_close_by_peer_total 1356
telemt_me_route_drop_no_conn_total 717470
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 836413
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3165
telemt_desync_full_logged_total 991
telemt_desync_suppressed_total 2174
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 1252
telemt_desync_frames_bucket_total{bucket="gt_10"} 1342
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 27
telemt_me_writer_removed_unexpected_total 1367
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1190
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 836681
telemt_user_connections_current{user="hello"} 3855
telemt_user_octets_from_client{user="hello"} 10463537226 (9.74 GB)
telemt_user_octets_to_client{user="hello"} 230322906066 (214.50 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1352
telemt_user_unique_ips_recent_window{user="hello"} 636
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 9144.6 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 938335
telemt_connections_bad_total 104011
telemt_connections_current 3140
telemt_connections_me_current 3140
telemt_handshake_timeouts_total 8967
telemt_upstream_connect_attempt_total 1543
telemt_upstream_connect_success_total 1529
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1915
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 974
telemt_me_idle_close_by_peer_total 973
telemt_me_route_drop_no_conn_total 844659
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 716582
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2484
telemt_desync_full_logged_total 667
telemt_desync_suppressed_total 1817
telemt_desync_frames_bucket_total{bucket="1_2"} 700
telemt_desync_frames_bucket_total{bucket="3_10"} 925
telemt_desync_frames_bucket_total{bucket="gt_10"} 859
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 976
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1007
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 713801
telemt_user_connections_current{user="hello"} 3140
telemt_user_octets_from_client{user="hello"} 7581543388 (7.06 GB)
telemt_user_octets_to_client{user="hello"} 193438507224 (180.15 GB)
telemt_user_unique_ips_current{user="hello"} 1052
telemt_user_unique_ips_recent_window{user="hello"} 499
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 9132.1 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 757195
telemt_connections_bad_total 47505
telemt_connections_current 2843
telemt_connections_me_current 2843
telemt_handshake_timeouts_total 11706
telemt_upstream_connect_attempt_total 10571
telemt_upstream_connect_success_total 10065
telemt_upstream_connect_fail_total 506
telemt_upstream_connect_attempts_per_request{bucket="1"} 10571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1779
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 506
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 1398
telemt_me_reconnect_success_total 1085
telemt_me_reader_eof_total 1074
telemt_me_idle_close_by_peer_total 1073
telemt_me_route_drop_no_conn_total 505654
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 633219
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2804
telemt_desync_full_logged_total 945
telemt_desync_suppressed_total 1859
telemt_desync_frames_bucket_total{bucket="1_2"} 585
telemt_desync_frames_bucket_total{bucket="3_10"} 1081
telemt_desync_frames_bucket_total{bucket="gt_10"} 1138
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 77
telemt_me_writer_removed_unexpected_total 1210
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 1081
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 641160
telemt_user_connections_current{user="hello"} 2843
telemt_user_octets_from_client{user="hello"} 13200028371 (12.29 GB)
telemt_user_octets_to_client{user="hello"} 146984930444 (136.89 GB)
telemt_user_msgs_from_client{user="hello"} 16739
telemt_user_msgs_to_client{user="hello"} 18599
telemt_user_unique_ips_current{user="hello"} 1006
telemt_user_unique_ips_recent_window{user="hello"} 452
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 62855.6 (17h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4432847
telemt_connections_bad_total 816655
telemt_connections_current 3586
telemt_connections_me_current 3586
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 85631
telemt_upstream_connect_attempt_total 63089
telemt_upstream_connect_success_total 60602
telemt_upstream_connect_fail_total 2487
telemt_upstream_connect_attempts_per_request{bucket="1"} 63089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1022
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2487
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 73673
telemt_me_reconnect_success_total 8275
telemt_me_reader_eof_total 8705
telemt_me_idle_close_by_peer_total 8702
telemt_me_route_drop_no_conn_total 2105082
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3050777
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
telemt_desync_total 13160
telemt_desync_full_logged_total 4043
telemt_desync_suppressed_total 9117
telemt_desync_frames_bucket_total{bucket="1_2"} 2224
telemt_desync_frames_bucket_total{bucket="3_10"} 5637
telemt_desync_frames_bucket_total{bucket="gt_10"} 5299
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8492
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 8251
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 3099398
telemt_user_connections_current{user="hello"} 3586
telemt_user_octets_from_client{user="hello"} 48934581595 (45.57 GB)
telemt_user_octets_to_client{user="hello"} 1097168291640 (1021.82 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1182
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 9097.5 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207474
telemt_connections_bad_total 13968
telemt_connections_current 1126
telemt_connections_me_current 1126
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 6298
telemt_upstream_connect_attempt_total 4359
telemt_upstream_connect_success_total 4222
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 4359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1215
telemt_me_reconnect_success_total 1185
telemt_me_reader_eof_total 1172
telemt_me_idle_close_by_peer_total 1172
telemt_me_route_drop_no_conn_total 130637
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174731
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
telemt_desync_total 529
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 362
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 6
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 46
telemt_me_writer_removed_unexpected_total 1156
telemt_me_writer_restored_same_endpoint_total 1176
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 177345
telemt_user_connections_current{user="hello"} 1126
telemt_user_octets_from_client{user="hello"} 2472350612 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 45839584834 (42.69 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 9096.8 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619697
telemt_connections_bad_total 40175
telemt_connections_current 3056
telemt_connections_me_current 3056
telemt_handshake_timeouts_total 10866
telemt_upstream_connect_attempt_total 1511
telemt_upstream_connect_success_total 1499
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 995
telemt_me_reconnect_success_total 977
telemt_me_reader_eof_total 1005
telemt_me_idle_close_by_peer_total 1005
telemt_me_route_drop_no_conn_total 219593
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 535064
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2978
telemt_desync_full_logged_total 902
telemt_desync_suppressed_total 2076
telemt_desync_frames_bucket_total{bucket="1_2"} 579
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 1408
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 1004
telemt_me_writer_restored_same_endpoint_total 960
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 534678
telemt_user_connections_current{user="hello"} 3056
telemt_user_octets_from_client{user="hello"} 7704578520 (7.18 GB)
telemt_user_octets_to_client{user="hello"} 225904205340 (210.39 GB)
telemt_user_unique_ips_current{user="hello"} 1027
telemt_user_unique_ips_recent_window{user="hello"} 424
```