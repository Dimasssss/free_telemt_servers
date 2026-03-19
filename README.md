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

# Server Metrics 2026-03-19 17:21:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 210.3 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11256
telemt_connections_bad_total 176
telemt_connections_current 1689
telemt_connections_me_current 1689
telemt_handshake_timeouts_total 192
telemt_upstream_connect_attempt_total 99
telemt_upstream_connect_success_total 97
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 99
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 31
telemt_me_reconnect_success_total 31
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 2135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9839
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 32
telemt_me_writer_restored_same_endpoint_total 18
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 9838
telemt_user_connections_current{user="hello"} 1689
telemt_user_octets_from_client{user="hello"} 62545760 (59.65 MB)
telemt_user_octets_to_client{user="hello"} 1902028452 (1.77 GB)
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 16665.4 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1720481
telemt_connections_bad_total 87973
telemt_connections_current 3622
telemt_connections_me_current 3622
telemt_handshake_timeouts_total 32611
telemt_upstream_connect_attempt_total 4128
telemt_upstream_connect_success_total 4078
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 4128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6195
telemt_me_reconnect_success_total 1972
telemt_me_reader_eof_total 2134
telemt_me_idle_close_by_peer_total 2134
telemt_me_route_drop_no_conn_total 1034403
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1413204
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5417
telemt_desync_full_logged_total 1677
telemt_desync_suppressed_total 3740
telemt_desync_frames_bucket_total{bucket="1_2"} 1068
telemt_desync_frames_bucket_total{bucket="3_10"} 2120
telemt_desync_frames_bucket_total{bucket="gt_10"} 2229
telemt_pool_swap_total 10
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2112
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1917
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 1413216
telemt_user_connections_current{user="hello"} 3622
telemt_user_octets_from_client{user="hello"} 20628973006 (19.21 GB)
telemt_user_octets_to_client{user="hello"} 443811162122 (413.33 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1293
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 16643.8 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1601744
telemt_connections_bad_total 193898
telemt_connections_current 2747
telemt_connections_me_current 2747
telemt_handshake_timeouts_total 16341
telemt_upstream_connect_attempt_total 2703
telemt_upstream_connect_success_total 2684
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2723
telemt_me_reconnect_success_total 1805
telemt_me_reader_eof_total 1820
telemt_me_idle_close_by_peer_total 1819
telemt_me_route_drop_no_conn_total 1505438
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1214625
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3886
telemt_desync_full_logged_total 1132
telemt_desync_suppressed_total 2754
telemt_desync_frames_bucket_total{bucket="1_2"} 1042
telemt_desync_frames_bucket_total{bucket="3_10"} 1446
telemt_desync_frames_bucket_total{bucket="gt_10"} 1398
telemt_pool_swap_total 12
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 1790
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1804
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1211822
telemt_user_connections_current{user="hello"} 2747
telemt_user_octets_from_client{user="hello"} 14477003728 (13.48 GB)
telemt_user_octets_to_client{user="hello"} 356181780292 (331.72 GB)
telemt_user_unique_ips_current{user="hello"} 966
telemt_user_unique_ips_recent_window{user="hello"} 394
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 16631.3 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1371820
telemt_connections_bad_total 56534
telemt_connections_current 2918
telemt_connections_me_current 2918
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 20568
telemt_upstream_connect_attempt_total 19820
telemt_upstream_connect_success_total 18905
telemt_upstream_connect_fail_total 915
telemt_upstream_connect_attempts_per_request{bucket="1"} 19820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 915
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4355
telemt_me_reconnect_success_total 2091
telemt_me_reader_eof_total 2164
telemt_me_idle_close_by_peer_total 2163
telemt_me_route_drop_no_conn_total 1051215
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1175868
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4871
telemt_desync_full_logged_total 1521
telemt_desync_suppressed_total 3350
telemt_desync_frames_bucket_total{bucket="1_2"} 1289
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 1785
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_removed_unexpected_total 2420
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2087
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 1191174
telemt_user_connections_current{user="hello"} 2918
telemt_user_octets_from_client{user="hello"} 22980927361 (21.40 GB)
telemt_user_octets_to_client{user="hello"} 270459349422 (251.88 GB)
telemt_user_msgs_from_client{user="hello"} 40382
telemt_user_msgs_to_client{user="hello"} 85113
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 418
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 70354.8 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5041535
telemt_connections_bad_total 867599
telemt_connections_current 3459
telemt_connections_me_current 3459
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 95768
telemt_upstream_connect_attempt_total 64336
telemt_upstream_connect_success_total 61845
telemt_upstream_connect_fail_total 2491
telemt_upstream_connect_attempts_per_request{bucket="1"} 64336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1037
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74523
telemt_me_reconnect_success_total 9119
telemt_me_reader_eof_total 9602
telemt_me_idle_close_by_peer_total 9599
telemt_me_route_drop_no_conn_total 2390718
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3540673
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
telemt_desync_total 15460
telemt_desync_full_logged_total 4705
telemt_desync_suppressed_total 10755
telemt_desync_frames_bucket_total{bucket="1_2"} 2524
telemt_desync_frames_bucket_total{bucket="3_10"} 6499
telemt_desync_frames_bucket_total{bucket="gt_10"} 6437
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 9354
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9095
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 3588821
telemt_user_connections_current{user="hello"} 3459
telemt_user_octets_from_client{user="hello"} 55977237659 (52.13 GB)
telemt_user_octets_to_client{user="hello"} 1301303248648 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1138
telemt_user_unique_ips_recent_window{user="hello"} 493
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 16596.3 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346301
telemt_connections_bad_total 26653
telemt_connections_current 733
telemt_connections_me_current 733
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 7598
telemt_upstream_connect_attempt_total 5954
telemt_upstream_connect_success_total 5817
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 5954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 2437
telemt_me_reconnect_success_total 2398
telemt_me_reader_eof_total 2442
telemt_me_idle_close_by_peer_total 2442
telemt_me_route_drop_no_conn_total 208981
telemt_me_route_drop_channel_closed_total 57
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291688
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
telemt_desync_total 887
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 612
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 409
telemt_pool_swap_total 10
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 63
telemt_me_writer_removed_unexpected_total 2387
telemt_me_writer_restored_same_endpoint_total 2389
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 294262
telemt_user_connections_current{user="hello"} 733
telemt_user_octets_from_client{user="hello"} 4074903748 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 76235339178 (71.00 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 16596.1 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1119338
telemt_connections_bad_total 75280
telemt_connections_current 3134
telemt_connections_me_current 3134
telemt_handshake_timeouts_total 19149
telemt_upstream_connect_attempt_total 2836
telemt_upstream_connect_success_total 2814
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 1954
telemt_me_reconnect_success_total 1930
telemt_me_reader_eof_total 2015
telemt_me_idle_close_by_peer_total 2015
telemt_me_route_drop_no_conn_total 445067
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 960039
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5359
telemt_desync_full_logged_total 1614
telemt_desync_suppressed_total 3745
telemt_desync_frames_bucket_total{bucket="1_2"} 1088
telemt_desync_frames_bucket_total{bucket="3_10"} 1842
telemt_desync_frames_bucket_total{bucket="gt_10"} 2429
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 1969
telemt_me_writer_restored_same_endpoint_total 1913
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 959589
telemt_user_connections_current{user="hello"} 3134
telemt_user_octets_from_client{user="hello"} 14776229108 (13.76 GB)
telemt_user_octets_to_client{user="hello"} 413515471012 (385.12 GB)
telemt_user_unique_ips_current{user="hello"} 1044
telemt_user_unique_ips_recent_window{user="hello"} 405
```