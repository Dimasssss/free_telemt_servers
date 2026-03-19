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

# Server Metrics 2026-03-19 17:46:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 1741.1 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58813
telemt_connections_bad_total 1583
telemt_connections_current 1664
telemt_connections_me_current 1664
telemt_handshake_timeouts_total 611
telemt_upstream_connect_attempt_total 253
telemt_upstream_connect_success_total 249
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 140
telemt_me_reconnect_success_total 139
telemt_me_reader_eof_total 124
telemt_me_idle_close_by_peer_total 124
telemt_me_route_drop_no_conn_total 19944
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51420
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 247
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 146
telemt_me_writer_restored_same_endpoint_total 126
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 51495
telemt_user_connections_current{user="hello"} 1664
telemt_user_octets_from_client{user="hello"} 905955536 (863.99 MB)
telemt_user_octets_to_client{user="hello"} 18563455192 (17.29 GB)
telemt_user_unique_ips_current{user="hello"} 450
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 18196.8 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1844623
telemt_connections_bad_total 92112
telemt_connections_current 3911
telemt_connections_me_current 3911
telemt_handshake_timeouts_total 34644
telemt_upstream_connect_attempt_total 4352
telemt_upstream_connect_success_total 4298
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 4352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6329
telemt_me_reconnect_success_total 2106
telemt_me_reader_eof_total 2281
telemt_me_idle_close_by_peer_total 2281
telemt_me_route_drop_no_conn_total 1084910
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1524965
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5937
telemt_desync_full_logged_total 1856
telemt_desync_suppressed_total 4081
telemt_desync_frames_bucket_total{bucket="1_2"} 1167
telemt_desync_frames_bucket_total{bucket="3_10"} 2346
telemt_desync_frames_bucket_total{bucket="gt_10"} 2424
telemt_pool_swap_total 12
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2250
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2051
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 1524959
telemt_user_connections_current{user="hello"} 3911
telemt_user_octets_from_client{user="hello"} 22674861286 (21.12 GB)
telemt_user_octets_to_client{user="hello"} 484450403854 (451.18 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1337
telemt_user_unique_ips_recent_window{user="hello"} 572
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 18175.0 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1711780
telemt_connections_bad_total 208277
telemt_connections_current 2909
telemt_connections_me_current 2909
telemt_handshake_timeouts_total 18046
telemt_upstream_connect_attempt_total 2929
telemt_upstream_connect_success_total 2910
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2863
telemt_me_reconnect_success_total 1945
telemt_me_reader_eof_total 1972
telemt_me_idle_close_by_peer_total 1971
telemt_me_route_drop_no_conn_total 1541083
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1297059
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4054
telemt_desync_full_logged_total 1204
telemt_desync_suppressed_total 2850
telemt_desync_frames_bucket_total{bucket="1_2"} 1066
telemt_desync_frames_bucket_total{bucket="3_10"} 1518
telemt_desync_frames_bucket_total{bucket="gt_10"} 1470
telemt_pool_swap_total 14
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 1932
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1944
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1294179
telemt_user_connections_current{user="hello"} 2909
telemt_user_octets_from_client{user="hello"} 16333598716 (15.21 GB)
telemt_user_octets_to_client{user="hello"} 392217429636 (365.28 GB)
telemt_user_unique_ips_current{user="hello"} 977
telemt_user_unique_ips_recent_window{user="hello"} 425
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 18162.6 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1557195
telemt_connections_bad_total 58301
telemt_connections_current 3094
telemt_connections_me_current 3094
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 21642
telemt_upstream_connect_attempt_total 20116
telemt_upstream_connect_success_total 19188
telemt_upstream_connect_fail_total 928
telemt_upstream_connect_attempts_per_request{bucket="1"} 20116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3113
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 337
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 928
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4557
telemt_me_reconnect_success_total 2286
telemt_me_reader_eof_total 2371
telemt_me_idle_close_by_peer_total 2370
telemt_me_route_drop_no_conn_total 1364808
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1344003
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5330
telemt_desync_full_logged_total 1674
telemt_desync_suppressed_total 3656
telemt_desync_frames_bucket_total{bucket="1_2"} 1397
telemt_desync_frames_bucket_total{bucket="3_10"} 1969
telemt_desync_frames_bucket_total{bucket="gt_10"} 1964
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_removed_unexpected_total 2617
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2282
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 1359297
telemt_user_connections_current{user="hello"} 3094
telemt_user_octets_from_client{user="hello"} 25226005929 (23.49 GB)
telemt_user_octets_to_client{user="hello"} 294016192274 (273.82 GB)
telemt_user_msgs_from_client{user="hello"} 40382
telemt_user_msgs_to_client{user="hello"} 85113
telemt_user_unique_ips_current{user="hello"} 988
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 71885.7 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5179546
telemt_connections_bad_total 904824
telemt_connections_current 3331
telemt_connections_me_current 3331
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 96893
telemt_upstream_connect_attempt_total 64520
telemt_upstream_connect_success_total 62029
telemt_upstream_connect_fail_total 2491
telemt_upstream_connect_attempts_per_request{bucket="1"} 64520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74664
telemt_me_reconnect_success_total 9258
telemt_me_reader_eof_total 9751
telemt_me_idle_close_by_peer_total 9748
telemt_me_route_drop_no_conn_total 2432697
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3630177
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
telemt_desync_total 15865
telemt_desync_full_logged_total 4837
telemt_desync_suppressed_total 11028
telemt_desync_frames_bucket_total{bucket="1_2"} 2608
telemt_desync_frames_bucket_total{bucket="3_10"} 6639
telemt_desync_frames_bucket_total{bucket="gt_10"} 6618
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9495
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9234
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 3678311
telemt_user_connections_current{user="hello"} 3331
telemt_user_octets_from_client{user="hello"} 57419698607 (53.48 GB)
telemt_user_octets_to_client{user="hello"} 1342778555504 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1126
telemt_user_unique_ips_recent_window{user="hello"} 488
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 18126.9 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372048
telemt_connections_bad_total 29292
telemt_connections_current 909
telemt_connections_me_current 909
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 7921
telemt_upstream_connect_attempt_total 6192
telemt_upstream_connect_success_total 6054
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 6192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_reconnect_attempts_total 2589
telemt_me_reconnect_success_total 2549
telemt_me_reader_eof_total 2604
telemt_me_idle_close_by_peer_total 2604
telemt_me_route_drop_no_conn_total 225225
telemt_me_route_drop_channel_closed_total 64
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313179
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
telemt_desync_total 961
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 666
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 387
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 11
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 67
telemt_me_writer_removed_unexpected_total 2546
telemt_me_writer_restored_same_endpoint_total 2540
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 315752
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 4316000712 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 81069903474 (75.50 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 18127.1 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1212782
telemt_connections_bad_total 82886
telemt_connections_current 3028
telemt_connections_me_current 3028
telemt_handshake_timeouts_total 20021
telemt_upstream_connect_attempt_total 3055
telemt_upstream_connect_success_total 3032
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 3055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 2086
telemt_me_reconnect_success_total 2061
telemt_me_reader_eof_total 2152
telemt_me_idle_close_by_peer_total 2152
telemt_me_route_drop_no_conn_total 473469
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1041591
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5741
telemt_desync_full_logged_total 1743
telemt_desync_suppressed_total 3998
telemt_desync_frames_bucket_total{bucket="1_2"} 1144
telemt_desync_frames_bucket_total{bucket="3_10"} 1981
telemt_desync_frames_bucket_total{bucket="gt_10"} 2616
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 2102
telemt_me_writer_restored_same_endpoint_total 2044
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1041139
telemt_user_connections_current{user="hello"} 3028
telemt_user_octets_from_client{user="hello"} 15916827672 (14.82 GB)
telemt_user_octets_to_client{user="hello"} 451277735612 (420.29 GB)
telemt_user_unique_ips_current{user="hello"} 996
telemt_user_unique_ips_recent_window{user="hello"} 413
```