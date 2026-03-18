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

# Server Metrics 2026-03-18 21:47:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22924.5 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516137
telemt_connections_bad_total 31498
telemt_handshake_timeouts_total 9882
telemt_upstream_connect_attempt_total 4144
telemt_upstream_connect_success_total 4141
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 2993
telemt_me_reconnect_success_total 2976
telemt_me_reader_eof_total 3113
telemt_me_idle_close_by_peer_total 3113
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 206318
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 437856
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2639
telemt_desync_full_logged_total 795
telemt_desync_suppressed_total 1844
telemt_desync_frames_bucket_total{bucket="1_2"} 602
telemt_desync_frames_bucket_total{bucket="3_10"} 844
telemt_desync_frames_bucket_total{bucket="gt_10"} 1193
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3029
telemt_me_writer_restored_same_endpoint_total 2956
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 437665
telemt_user_connections_current{user="hello"} 851
telemt_user_octets_from_client{user="hello"} 8333065524 (7.76 GB)
telemt_user_octets_to_client{user="hello"} 164495825736 (153.20 GB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 27752.2 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2285835
telemt_connections_bad_total 160694
telemt_connections_current 2275
telemt_connections_me_current 2275
telemt_handshake_timeouts_total 37523
telemt_upstream_connect_attempt_total 4289
telemt_upstream_connect_success_total 4262
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 4289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 2895
telemt_me_reconnect_success_total 2874
telemt_me_reader_eof_total 2938
telemt_me_idle_close_by_peer_total 2937
telemt_me_route_drop_no_conn_total 1887611
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1977363
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7137
telemt_desync_full_logged_total 2339
telemt_desync_suppressed_total 4798
telemt_desync_frames_bucket_total{bucket="1_2"} 1239
telemt_desync_frames_bucket_total{bucket="3_10"} 2805
telemt_desync_frames_bucket_total{bucket="gt_10"} 3093
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 2847
telemt_me_writer_restored_same_endpoint_total 2872
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1972751
telemt_user_connections_current{user="hello"} 2275
telemt_user_octets_from_client{user="hello"} 32946832348 (30.68 GB)
telemt_user_octets_to_client{user="hello"} 708933498164 (660.25 GB)
telemt_user_unique_ips_current{user="hello"} 824
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 27680.8 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1761736
telemt_connections_bad_total 148490
telemt_connections_current 1960
telemt_connections_me_current 1960
telemt_handshake_timeouts_total 41851
telemt_upstream_connect_attempt_total 4008
telemt_upstream_connect_success_total 3987
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 2618
telemt_me_reconnect_success_total 2597
telemt_me_reader_eof_total 2762
telemt_me_idle_close_by_peer_total 2762
telemt_me_route_drop_no_conn_total 709022
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1422362
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6846
telemt_desync_full_logged_total 2095
telemt_desync_suppressed_total 4751
telemt_desync_frames_bucket_total{bucket="1_2"} 1690
telemt_desync_frames_bucket_total{bucket="3_10"} 2561
telemt_desync_frames_bucket_total{bucket="gt_10"} 2595
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 2659
telemt_me_writer_restored_same_endpoint_total 2580
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1421554
telemt_user_connections_current{user="hello"} 1960
telemt_user_octets_from_client{user="hello"} 30204654568 (28.13 GB)
telemt_user_octets_to_client{user="hello"} 735898489704 (685.36 GB)
telemt_user_unique_ips_current{user="hello"} 705
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 180.2 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10244
telemt_connections_bad_total 519
telemt_connections_current 1518
telemt_connections_direct_current 1518
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_demotions_total 137
telemt_relay_adaptive_hard_promotions_total 16
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 8145
telemt_upstream_connect_success_total 8138
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 8145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 4147
telemt_me_reconnect_success_total 195
telemt_me_reader_eof_total 95
telemt_me_idle_close_by_peer_total 95
telemt_me_route_drop_no_conn_total 258
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1129
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 116
telemt_me_refill_failed_total 219
telemt_me_writer_restored_same_endpoint_total 93
telemt_me_writer_restored_fallback_total 102
telemt_me_no_writer_failfast_total 120
telemt_me_async_recovery_trigger_total 1540
telemt_user_connections_total{user="hello"} 9127
telemt_user_connections_current{user="hello"} 1518
telemt_user_octets_from_client{user="hello"} 36001586 (34.33 MB)
telemt_user_octets_to_client{user="hello"} 1547775091 (1.44 GB)
telemt_user_msgs_from_client{user="hello"} 65722
telemt_user_msgs_to_client{user="hello"} 432209
telemt_user_unique_ips_current{user="hello"} 502
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 22910.0 (6h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1439822
telemt_connections_bad_total 236649
telemt_handshake_timeouts_total 14038
telemt_upstream_connect_attempt_total 4301
telemt_upstream_connect_success_total 4167
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 4301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 8748
telemt_me_reconnect_success_total 2999
telemt_me_reader_eof_total 3264
telemt_me_idle_close_by_peer_total 3264
telemt_me_route_drop_no_conn_total 589597
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1074098
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4356
telemt_desync_full_logged_total 1565
telemt_desync_suppressed_total 2791
telemt_desync_frames_bucket_total{bucket="1_2"} 751
telemt_desync_frames_bucket_total{bucket="3_10"} 1508
telemt_desync_frames_bucket_total{bucket="gt_10"} 2097
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 3228
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2973
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 1073456
telemt_user_connections_current{user="hello"} 1881
telemt_user_octets_from_client{user="hello"} 19328262804 (18.00 GB)
telemt_user_octets_to_client{user="hello"} 539421229228 (502.38 GB)
telemt_user_unique_ips_current{user="hello"} 749
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## hostvds.com

Не удалось получить метрики для этого сервера.

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 26914.5 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1425658
telemt_connections_bad_total 113039
telemt_connections_current 1709
telemt_connections_me_current 1709
telemt_handshake_timeouts_total 31701
telemt_upstream_connect_attempt_total 4425
telemt_upstream_connect_success_total 4424
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 18597
telemt_me_reconnect_success_total 3071
telemt_me_reader_eof_total 3161
telemt_me_idle_close_by_peer_total 3160
telemt_me_route_drop_no_conn_total 626012
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1192861
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5920
telemt_desync_full_logged_total 1908
telemt_desync_suppressed_total 4012
telemt_desync_frames_bucket_total{bucket="1_2"} 1491
telemt_desync_frames_bucket_total{bucket="3_10"} 1975
telemt_desync_frames_bucket_total{bucket="gt_10"} 2454
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3063
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 3010
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 1191544
telemt_user_connections_current{user="hello"} 1709
telemt_user_octets_from_client{user="hello"} 23547172712 (21.93 GB)
telemt_user_octets_to_client{user="hello"} 701326826060 (653.16 GB)
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 163
```