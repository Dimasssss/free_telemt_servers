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

# Server Metrics 2026-03-19 19:28:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 7877.1 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246761
telemt_connections_bad_total 10378
telemt_connections_current 1247
telemt_connections_me_current 1247
telemt_handshake_timeouts_total 2534
telemt_upstream_connect_attempt_total 1186
telemt_upstream_connect_success_total 1172
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 761
telemt_me_reconnect_success_total 755
telemt_me_reader_eof_total 783
telemt_me_idle_close_by_peer_total 783
telemt_me_route_drop_no_conn_total 73977
telemt_me_route_drop_channel_closed_total 35
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191400
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 921
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 620
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 455
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 777
telemt_me_writer_restored_same_endpoint_total 742
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 191659
telemt_user_connections_current{user="hello"} 1247
telemt_user_octets_from_client{user="hello"} 6077605968 (5.66 GB)
telemt_user_octets_to_client{user="hello"} 67718689976 (63.07 GB)
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 24332.7 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2315914
telemt_connections_bad_total 103649
telemt_connections_current 3606
telemt_connections_me_current 3606
telemt_handshake_timeouts_total 44031
telemt_upstream_connect_attempt_total 5246
telemt_upstream_connect_success_total 5177
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 5246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6944
telemt_me_reconnect_success_total 2716
telemt_me_reader_eof_total 2933
telemt_me_idle_close_by_peer_total 2933
telemt_me_route_drop_no_conn_total 1271283
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1950819
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8105
telemt_desync_full_logged_total 2621
telemt_desync_suppressed_total 5484
telemt_desync_frames_bucket_total{bucket="1_2"} 1498
telemt_desync_frames_bucket_total{bucket="3_10"} 3198
telemt_desync_frames_bucket_total{bucket="gt_10"} 3409
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2870
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2661
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 1950813
telemt_user_connections_current{user="hello"} 3606
telemt_user_octets_from_client{user="hello"} 28540358606 (26.58 GB)
telemt_user_octets_to_client{user="hello"} 656498316470 (611.41 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1236
telemt_user_unique_ips_recent_window{user="hello"} 424
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 24311.1 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2097147
telemt_connections_bad_total 247388
telemt_connections_current 2738
telemt_connections_me_current 2738
telemt_handshake_timeouts_total 24502
telemt_upstream_connect_attempt_total 3751
telemt_upstream_connect_success_total 3726
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3419
telemt_me_reconnect_success_total 2500
telemt_me_reader_eof_total 2567
telemt_me_idle_close_by_peer_total 2566
telemt_me_route_drop_no_conn_total 1746920
telemt_me_route_drop_channel_closed_total 152
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1596610
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5633
telemt_desync_full_logged_total 1680
telemt_desync_suppressed_total 3953
telemt_desync_frames_bucket_total{bucket="1_2"} 1434
telemt_desync_frames_bucket_total{bucket="3_10"} 2137
telemt_desync_frames_bucket_total{bucket="gt_10"} 2062
telemt_pool_swap_total 20
telemt_me_writer_close_signal_drop_total 54
telemt_me_writer_removed_unexpected_total 2501
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2499
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1592965
telemt_user_connections_current{user="hello"} 2738
telemt_user_octets_from_client{user="hello"} 22193353872 (20.67 GB)
telemt_user_octets_to_client{user="hello"} 538076389080 (501.12 GB)
telemt_user_unique_ips_current{user="hello"} 891
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 24298.5 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1973382
telemt_connections_bad_total 64523
telemt_connections_current 2525
telemt_connections_me_current 2525
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 25121
telemt_upstream_connect_attempt_total 25809
telemt_upstream_connect_success_total 24601
telemt_upstream_connect_fail_total 1208
telemt_upstream_connect_attempts_per_request{bucket="1"} 25809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1208
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5341
telemt_me_reconnect_success_total 2949
telemt_me_reader_eof_total 3062
telemt_me_idle_close_by_peer_total 3061
telemt_me_route_drop_no_conn_total 1690380
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1703660
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6856
telemt_desync_full_logged_total 2141
telemt_desync_suppressed_total 4715
telemt_desync_frames_bucket_total{bucket="1_2"} 1717
telemt_desync_frames_bucket_total{bucket="3_10"} 2516
telemt_desync_frames_bucket_total{bucket="gt_10"} 2623
telemt_pool_swap_total 11
telemt_me_writer_close_signal_drop_total 201
telemt_me_writer_removed_unexpected_total 3368
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2945
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 1722982
telemt_user_connections_current{user="hello"} 2525
telemt_user_octets_from_client{user="hello"} 29709890949 (27.67 GB)
telemt_user_octets_to_client{user="hello"} 390472353297 (363.66 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 900
telemt_user_unique_ips_recent_window{user="hello"} 325
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 78021.8 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5659143
telemt_connections_bad_total 1015469
telemt_connections_current 2879
telemt_connections_me_current 2879
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 103444
telemt_upstream_connect_attempt_total 65360
telemt_upstream_connect_success_total 62863
telemt_upstream_connect_fail_total 2497
telemt_upstream_connect_attempts_per_request{bucket="1"} 65360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2497
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75195
telemt_me_reconnect_success_total 9784
telemt_me_reader_eof_total 10320
telemt_me_idle_close_by_peer_total 10317
telemt_me_route_drop_no_conn_total 2593553
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3956283
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
telemt_desync_total 17438
telemt_desync_full_logged_total 5366
telemt_desync_suppressed_total 12072
telemt_desync_frames_bucket_total{bucket="1_2"} 2912
telemt_desync_frames_bucket_total{bucket="3_10"} 7243
telemt_desync_frames_bucket_total{bucket="gt_10"} 7283
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 10037
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9760
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 4004387
telemt_user_connections_current{user="hello"} 2879
telemt_user_octets_from_client{user="hello"} 62467475451 (58.18 GB)
telemt_user_octets_to_client{user="hello"} 1490175945008 (1.36 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1002
telemt_user_unique_ips_recent_window{user="hello"} 399
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 24262.0 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 543616
telemt_connections_bad_total 41278
telemt_connections_current 591
telemt_connections_me_current 591
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10773
telemt_upstream_connect_attempt_total 7575
telemt_upstream_connect_success_total 7378
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 549
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 3219
telemt_me_reconnect_success_total 3161
telemt_me_reader_eof_total 3254
telemt_me_idle_close_by_peer_total 3253
telemt_me_route_drop_no_conn_total 372864
telemt_me_route_drop_channel_closed_total 132
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430496
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1121
telemt_desync_full_logged_total 354
telemt_desync_suppressed_total 767
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 455
telemt_desync_frames_bucket_total{bucket="gt_10"} 490
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 135
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3185
telemt_me_writer_restored_same_endpoint_total 3152
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 449137
telemt_user_connections_current{user="hello"} 591
telemt_user_octets_from_client{user="hello"} 5145666756 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 94431026686 (87.95 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 24263.3 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1553338
telemt_connections_bad_total 93747
telemt_connections_current 2789
telemt_connections_me_current 2789
telemt_handshake_timeouts_total 25648
telemt_upstream_connect_attempt_total 3978
telemt_upstream_connect_success_total 3948
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 3978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 2744
telemt_me_reconnect_success_total 2715
telemt_me_reader_eof_total 2849
telemt_me_idle_close_by_peer_total 2849
telemt_me_route_drop_no_conn_total 593132
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1348759
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7076
telemt_desync_full_logged_total 2184
telemt_desync_suppressed_total 4892
telemt_desync_frames_bucket_total{bucket="1_2"} 1339
telemt_desync_frames_bucket_total{bucket="3_10"} 2459
telemt_desync_frames_bucket_total{bucket="gt_10"} 3278
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2772
telemt_me_writer_restored_same_endpoint_total 2698
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 1348009
telemt_user_connections_current{user="hello"} 2789
telemt_user_octets_from_client{user="hello"} 21561217848 (20.08 GB)
telemt_user_octets_to_client{user="hello"} 617893879204 (575.46 GB)
telemt_user_unique_ips_current{user="hello"} 929
telemt_user_unique_ips_recent_window{user="hello"} 337
```