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

# Server Metrics 2026-03-19 22:40:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 19381.8 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432008
telemt_connections_bad_total 26383
telemt_connections_current 776
telemt_connections_me_current 776
telemt_handshake_timeouts_total 6217
telemt_upstream_connect_attempt_total 3196
telemt_upstream_connect_success_total 3168
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2196
telemt_me_reconnect_success_total 2179
telemt_me_reader_eof_total 2310
telemt_me_idle_close_by_peer_total 2310
telemt_me_route_drop_no_conn_total 128754
telemt_me_route_drop_channel_closed_total 51
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342145
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1835
telemt_desync_full_logged_total 648
telemt_desync_suppressed_total 1187
telemt_desync_frames_bucket_total{bucket="1_2"} 381
telemt_desync_frames_bucket_total{bucket="3_10"} 591
telemt_desync_frames_bucket_total{bucket="gt_10"} 863
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 2226
telemt_me_writer_restored_same_endpoint_total 2166
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 342405
telemt_user_connections_current{user="hello"} 776
telemt_user_octets_from_client{user="hello"} 14236874396 (13.26 GB)
telemt_user_octets_to_client{user="hello"} 127815766940 (119.04 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 35836.9 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2802095
telemt_connections_bad_total 120204
telemt_connections_current 1565
telemt_connections_me_current 1565
telemt_handshake_timeouts_total 56549
telemt_upstream_connect_attempt_total 7248
telemt_upstream_connect_success_total 7135
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 7248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8345
telemt_me_reconnect_success_total 4114
telemt_me_reader_eof_total 4417
telemt_me_idle_close_by_peer_total 4417
telemt_me_route_drop_no_conn_total 1448187
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2393089
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10588
telemt_desync_full_logged_total 3471
telemt_desync_suppressed_total 7117
telemt_desync_frames_bucket_total{bucket="1_2"} 1983
telemt_desync_frames_bucket_total{bucket="3_10"} 4139
telemt_desync_frames_bucket_total{bucket="gt_10"} 4466
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 4285
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4059
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 2392967
telemt_user_connections_current{user="hello"} 1565
telemt_user_octets_from_client{user="hello"} 37701822006 (35.11 GB)
telemt_user_octets_to_client{user="hello"} 859385496526 (800.37 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 710
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 35815.0 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2727662
telemt_connections_bad_total 461320
telemt_connections_current 1252
telemt_connections_me_current 1252
telemt_handshake_timeouts_total 35280
telemt_upstream_connect_attempt_total 5609
telemt_upstream_connect_success_total 5564
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 5609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4698
telemt_me_reconnect_success_total 3769
telemt_me_reader_eof_total 3926
telemt_me_idle_close_by_peer_total 3925
telemt_me_route_drop_no_conn_total 1869703
telemt_me_route_drop_channel_closed_total 168
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1902259
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7400
telemt_desync_full_logged_total 2238
telemt_desync_suppressed_total 5162
telemt_desync_frames_bucket_total{bucket="1_2"} 1822
telemt_desync_frames_bucket_total{bucket="3_10"} 2828
telemt_desync_frames_bucket_total{bucket="gt_10"} 2750
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 62
telemt_me_writer_removed_unexpected_total 3798
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3768
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1898080
telemt_user_connections_current{user="hello"} 1252
telemt_user_octets_from_client{user="hello"} 28667330832 (26.70 GB)
telemt_user_octets_to_client{user="hello"} 709575238584 (660.84 GB)
telemt_user_unique_ips_current{user="hello"} 521
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 35802.8 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2383922
telemt_connections_bad_total 99742
telemt_connections_current 1224
telemt_connections_me_current 1224
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29574
telemt_upstream_connect_attempt_total 35982
telemt_upstream_connect_success_total 34229
telemt_upstream_connect_fail_total 1753
telemt_upstream_connect_attempts_per_request{bucket="1"} 35982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 457
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1753
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6990
telemt_me_reconnect_success_total 4356
telemt_me_reader_eof_total 4520
telemt_me_idle_close_by_peer_total 4519
telemt_me_route_drop_no_conn_total 1831531
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2024552
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8107
telemt_desync_full_logged_total 2555
telemt_desync_suppressed_total 5552
telemt_desync_frames_bucket_total{bucket="1_2"} 1985
telemt_desync_frames_bucket_total{bucket="3_10"} 2946
telemt_desync_frames_bucket_total{bucket="gt_10"} 3176
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 349
telemt_me_writer_removed_unexpected_total 4882
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 4352
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 2051483
telemt_user_connections_current{user="hello"} 1224
telemt_user_octets_from_client{user="hello"} 33567607896 (31.26 GB)
telemt_user_octets_to_client{user="hello"} 536318293931 (499.49 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 89526.0 (24h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6060579
telemt_connections_bad_total 1036633
telemt_connections_current 1464
telemt_connections_me_current 1464
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 109610
telemt_upstream_connect_attempt_total 67266
telemt_upstream_connect_success_total 64758
telemt_upstream_connect_fail_total 2508
telemt_upstream_connect_attempts_per_request{bucket="1"} 67266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2508
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76529
telemt_me_reconnect_success_total 11110
telemt_me_reader_eof_total 11732
telemt_me_idle_close_by_peer_total 11729
telemt_me_route_drop_no_conn_total 2756316
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4309758
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
telemt_desync_total 18962
telemt_desync_full_logged_total 5900
telemt_desync_suppressed_total 13062
telemt_desync_frames_bucket_total{bucket="1_2"} 3313
telemt_desync_frames_bucket_total{bucket="3_10"} 7791
telemt_desync_frames_bucket_total{bucket="gt_10"} 7858
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 11377
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 11086
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 4357807
telemt_user_connections_current{user="hello"} 1464
telemt_user_octets_from_client{user="hello"} 67561633291 (62.92 GB)
telemt_user_octets_to_client{user="hello"} 1691283407128 (1.54 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 35766.0 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 639823
telemt_connections_bad_total 50413
telemt_connections_current 357
telemt_connections_me_current 357
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12403
telemt_upstream_connect_attempt_total 10106
telemt_upstream_connect_success_total 9865
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 10106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 591
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4838
telemt_me_reconnect_success_total 4752
telemt_me_reader_eof_total 4959
telemt_me_idle_close_by_peer_total 4957
telemt_me_route_drop_no_conn_total 449833
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 542344
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
telemt_desync_total 1362
telemt_desync_full_logged_total 508
telemt_desync_suppressed_total 854
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 558
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 147
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4797
telemt_me_writer_restored_same_endpoint_total 4743
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 529332
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 6962655901 (6.48 GB)
telemt_user_octets_to_client{user="hello"} 127360982216 (118.61 GB)
telemt_user_msgs_from_client{user="hello"} 8558
telemt_user_msgs_to_client{user="hello"} 13690
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 35767.5 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1892676
telemt_connections_bad_total 111703
telemt_connections_current 1388
telemt_connections_me_current 1388
telemt_handshake_timeouts_total 35257
telemt_upstream_connect_attempt_total 6057
telemt_upstream_connect_success_total 6012
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 6057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4245
telemt_me_reconnect_success_total 4210
telemt_me_reader_eof_total 4432
telemt_me_idle_close_by_peer_total 4432
telemt_me_route_drop_no_conn_total 705431
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1635948
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8757
telemt_desync_full_logged_total 2772
telemt_desync_suppressed_total 5985
telemt_desync_frames_bucket_total{bucket="1_2"} 1606
telemt_desync_frames_bucket_total{bucket="3_10"} 3067
telemt_desync_frames_bucket_total{bucket="gt_10"} 4084
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4284
telemt_me_writer_restored_same_endpoint_total 4193
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1635086
telemt_user_connections_current{user="hello"} 1388
telemt_user_octets_from_client{user="hello"} 27775929836 (25.87 GB)
telemt_user_octets_to_client{user="hello"} 822396997528 (765.92 GB)
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 135
```