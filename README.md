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

# Server Metrics 2026-03-19 17:41:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 1435.3 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50684
telemt_connections_bad_total 1265
telemt_connections_current 1640
telemt_connections_me_current 1640
telemt_handshake_timeouts_total 568
telemt_upstream_connect_attempt_total 234
telemt_upstream_connect_success_total 230
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 121
telemt_me_reconnect_success_total 120
telemt_me_reader_eof_total 105
telemt_me_idle_close_by_peer_total 105
telemt_me_route_drop_no_conn_total 17044
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44321
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 209
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 127
telemt_me_writer_restored_same_endpoint_total 107
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 44377
telemt_user_connections_current{user="hello"} 1640
telemt_user_octets_from_client{user="hello"} 785107936 (748.74 MB)
telemt_user_octets_to_client{user="hello"} 14950029524 (13.92 GB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 17891.0 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1820830
telemt_connections_bad_total 91624
telemt_connections_current 3689
telemt_connections_me_current 3689
telemt_handshake_timeouts_total 34323
telemt_upstream_connect_attempt_total 4272
telemt_upstream_connect_success_total 4218
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 4272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6292
telemt_me_reconnect_success_total 2069
telemt_me_reader_eof_total 2238
telemt_me_idle_close_by_peer_total 2238
telemt_me_route_drop_no_conn_total 1074223
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1503450
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5830
telemt_desync_full_logged_total 1816
telemt_desync_suppressed_total 4014
telemt_desync_frames_bucket_total{bucket="1_2"} 1151
telemt_desync_frames_bucket_total{bucket="3_10"} 2302
telemt_desync_frames_bucket_total{bucket="gt_10"} 2377
telemt_pool_swap_total 11
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2211
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2014
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 1503442
telemt_user_connections_current{user="hello"} 3689
telemt_user_octets_from_client{user="hello"} 22291470422 (20.76 GB)
telemt_user_octets_to_client{user="hello"} 476837948598 (444.09 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1285
telemt_user_unique_ips_recent_window{user="hello"} 524
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 17869.5 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1691730
telemt_connections_bad_total 206479
telemt_connections_current 2993
telemt_connections_me_current 2993
telemt_handshake_timeouts_total 17782
telemt_upstream_connect_attempt_total 2843
telemt_upstream_connect_success_total 2824
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2820
telemt_me_reconnect_success_total 1902
telemt_me_reader_eof_total 1923
telemt_me_idle_close_by_peer_total 1922
telemt_me_route_drop_no_conn_total 1533593
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1280901
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4012
telemt_desync_full_logged_total 1181
telemt_desync_suppressed_total 2831
telemt_desync_frames_bucket_total{bucket="1_2"} 1064
telemt_desync_frames_bucket_total{bucket="3_10"} 1498
telemt_desync_frames_bucket_total{bucket="gt_10"} 1450
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 1889
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1901
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1278042
telemt_user_connections_current{user="hello"} 2993
telemt_user_octets_from_client{user="hello"} 15756778788 (14.67 GB)
telemt_user_octets_to_client{user="hello"} 385313072700 (358.85 GB)
telemt_user_unique_ips_current{user="hello"} 1015
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 17857.1 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1524856
telemt_connections_bad_total 57823
telemt_connections_current 3229
telemt_connections_me_current 3229
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 21473
telemt_upstream_connect_attempt_total 20021
telemt_upstream_connect_success_total 19099
telemt_upstream_connect_fail_total 922
telemt_upstream_connect_attempts_per_request{bucket="1"} 20021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 922
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4510
telemt_me_reconnect_success_total 2240
telemt_me_reader_eof_total 2324
telemt_me_idle_close_by_peer_total 2323
telemt_me_route_drop_no_conn_total 1322112
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1314865
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5259
telemt_desync_full_logged_total 1655
telemt_desync_suppressed_total 3604
telemt_desync_frames_bucket_total{bucket="1_2"} 1382
telemt_desync_frames_bucket_total{bucket="3_10"} 1956
telemt_desync_frames_bucket_total{bucket="gt_10"} 1921
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_removed_unexpected_total 2570
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2236
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 1330163
telemt_user_connections_current{user="hello"} 3229
telemt_user_octets_from_client{user="hello"} 24935661589 (23.22 GB)
telemt_user_octets_to_client{user="hello"} 289636557318 (269.75 GB)
telemt_user_msgs_from_client{user="hello"} 40382
telemt_user_msgs_to_client{user="hello"} 85113
telemt_user_unique_ips_current{user="hello"} 1022
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 71580.4 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5153173
telemt_connections_bad_total 898757
telemt_connections_current 3628
telemt_connections_me_current 3628
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 96524
telemt_upstream_connect_attempt_total 64502
telemt_upstream_connect_success_total 62011
telemt_upstream_connect_fail_total 2491
telemt_upstream_connect_attempts_per_request{bucket="1"} 64502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74646
telemt_me_reconnect_success_total 9241
telemt_me_reader_eof_total 9733
telemt_me_idle_close_by_peer_total 9730
telemt_me_route_drop_no_conn_total 2425029
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3612509
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
telemt_desync_total 15794
telemt_desync_full_logged_total 4810
telemt_desync_suppressed_total 10984
telemt_desync_frames_bucket_total{bucket="1_2"} 2593
telemt_desync_frames_bucket_total{bucket="3_10"} 6608
telemt_desync_frames_bucket_total{bucket="gt_10"} 6593
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9477
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9217
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 3660636
telemt_user_connections_current{user="hello"} 3628
telemt_user_octets_from_client{user="hello"} 57216535667 (53.29 GB)
telemt_user_octets_to_client{user="hello"} 1334759547512 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1196
telemt_user_unique_ips_recent_window{user="hello"} 523
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 17821.5 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367325
telemt_connections_bad_total 29126
telemt_connections_current 989
telemt_connections_me_current 989
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 7857
telemt_upstream_connect_attempt_total 6128
telemt_upstream_connect_success_total 5990
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 6128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3669
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_reconnect_attempts_total 2568
telemt_me_reconnect_success_total 2528
telemt_me_reader_eof_total 2580
telemt_me_idle_close_by_peer_total 2580
telemt_me_route_drop_no_conn_total 222402
telemt_me_route_drop_channel_closed_total 64
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308933
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
telemt_desync_total 956
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 662
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 383
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 10
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 67
telemt_me_writer_removed_unexpected_total 2525
telemt_me_writer_restored_same_endpoint_total 2519
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 311506
telemt_user_connections_current{user="hello"} 989
telemt_user_octets_from_client{user="hello"} 4288467988 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 80172993694 (74.67 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 17821.6 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1194999
telemt_connections_bad_total 82007
telemt_connections_current 3179
telemt_connections_me_current 3179
telemt_handshake_timeouts_total 19738
telemt_upstream_connect_attempt_total 2988
telemt_upstream_connect_success_total 2965
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 2062
telemt_me_reconnect_success_total 2037
telemt_me_reader_eof_total 2128
telemt_me_idle_close_by_peer_total 2128
telemt_me_route_drop_no_conn_total 467732
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1025757
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5673
telemt_desync_full_logged_total 1720
telemt_desync_suppressed_total 3953
telemt_desync_frames_bucket_total{bucket="1_2"} 1136
telemt_desync_frames_bucket_total{bucket="3_10"} 1958
telemt_desync_frames_bucket_total{bucket="gt_10"} 2579
telemt_pool_swap_total 14
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 2078
telemt_me_writer_restored_same_endpoint_total 2020
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1025302
telemt_user_connections_current{user="hello"} 3179
telemt_user_octets_from_client{user="hello"} 15526637296 (14.46 GB)
telemt_user_octets_to_client{user="hello"} 444026884492 (413.53 GB)
telemt_user_unique_ips_current{user="hello"} 1036
telemt_user_unique_ips_recent_window{user="hello"} 430
```