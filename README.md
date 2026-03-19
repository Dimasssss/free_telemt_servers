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

# Server Metrics 2026-03-19 07:40:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 35518.9 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 626382
telemt_connections_bad_total 64368
telemt_connections_current 1410
telemt_connections_me_current 1410
telemt_handshake_timeouts_total 23919
telemt_upstream_connect_attempt_total 6835
telemt_upstream_connect_success_total 6708
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 6835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 6074
telemt_me_reconnect_success_total 4924
telemt_me_reader_eof_total 5227
telemt_me_idle_close_by_peer_total 5226
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 177810
telemt_me_route_drop_channel_closed_total 62
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 473628
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3228
telemt_desync_full_logged_total 906
telemt_desync_suppressed_total 2322
telemt_desync_frames_bucket_total{bucket="1_2"} 1142
telemt_desync_frames_bucket_total{bucket="3_10"} 1209
telemt_desync_frames_bucket_total{bucket="gt_10"} 877
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5014
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4907
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 470742
telemt_user_connections_current{user="hello"} 1410
telemt_user_octets_from_client{user="hello"} 6179076208 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 158223173436 (147.36 GB)
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 35523.3 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1485082
telemt_connections_bad_total 82565
telemt_connections_current 4170
telemt_connections_me_current 4170
telemt_handshake_timeouts_total 35463
telemt_upstream_connect_attempt_total 6676
telemt_upstream_connect_success_total 6548
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 6676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 5904
telemt_me_reconnect_success_total 4748
telemt_me_reader_eof_total 5041
telemt_me_idle_close_by_peer_total 5041
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 616226
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1220040
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5442
telemt_desync_full_logged_total 1820
telemt_desync_suppressed_total 3622
telemt_desync_frames_bucket_total{bucket="1_2"} 970
telemt_desync_frames_bucket_total{bucket="3_10"} 2066
telemt_desync_frames_bucket_total{bucket="gt_10"} 2406
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4874
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4727
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 1219952
telemt_user_connections_current{user="hello"} 4170
telemt_user_octets_from_client{user="hello"} 22385875424 (20.85 GB)
telemt_user_octets_to_client{user="hello"} 486024564848 (452.65 GB)
telemt_user_unique_ips_current{user="hello"} 1369
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 35573.5 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1310187
telemt_connections_bad_total 89819
telemt_connections_current 2892
telemt_connections_me_current 2892
telemt_handshake_timeouts_total 32257
telemt_upstream_connect_attempt_total 6229
telemt_upstream_connect_success_total 6229
telemt_upstream_connect_attempts_per_request{bucket="1"} 6229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3059
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 5482
telemt_me_reconnect_success_total 4420
telemt_me_reader_eof_total 4694
telemt_me_idle_close_by_peer_total 4693
telemt_me_route_drop_no_conn_total 491561
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 902572
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3410
telemt_desync_full_logged_total 1174
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 662
telemt_desync_frames_bucket_total{bucket="3_10"} 1327
telemt_desync_frames_bucket_total{bucket="gt_10"} 1421
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4516
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4396
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 901369
telemt_user_connections_current{user="hello"} 2892
telemt_user_octets_from_client{user="hello"} 12642291640 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 312990642700 (291.50 GB)
telemt_user_unique_ips_current{user="hello"} 970
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 35516.8 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1572248
telemt_connections_bad_total 422904
telemt_connections_current 3394
telemt_connections_me_current 3394
telemt_handshake_timeouts_total 33997
telemt_upstream_connect_attempt_total 6230
telemt_upstream_connect_success_total 6191
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 6230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 4434
telemt_me_reconnect_success_total 4402
telemt_me_reader_eof_total 4665
telemt_me_idle_close_by_peer_total 4665
telemt_me_route_drop_no_conn_total 395139
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 950085
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4593
telemt_desync_full_logged_total 1431
telemt_desync_suppressed_total 3162
telemt_desync_frames_bucket_total{bucket="1_2"} 1011
telemt_desync_frames_bucket_total{bucket="3_10"} 2078
telemt_desync_frames_bucket_total{bucket="gt_10"} 1504
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 4458
telemt_me_writer_restored_same_endpoint_total 4378
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 949769
telemt_user_connections_current{user="hello"} 3394
telemt_user_octets_from_client{user="hello"} 20241135228 (18.85 GB)
telemt_user_octets_to_client{user="hello"} 462321298856 (430.57 GB)
telemt_user_unique_ips_current{user="hello"} 1146
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 35528.9 (9h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264850
telemt_connections_bad_total 13088
telemt_connections_current 913
telemt_connections_me_current 913
telemt_handshake_timeouts_total 2280
telemt_upstream_connect_attempt_total 9304
telemt_upstream_connect_success_total 9062
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 9304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 12644
telemt_me_reconnect_success_total 7268
telemt_me_reader_eof_total 7718
telemt_me_idle_close_by_peer_total 7718
telemt_me_route_drop_no_conn_total 124224
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236075
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 356
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 7482
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7238
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 236048
telemt_user_connections_current{user="hello"} 913
telemt_user_octets_from_client{user="hello"} 3567179484 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 114352282760 (106.50 GB)
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 35519.3 (9h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1000061
telemt_connections_bad_total 92472
telemt_connections_current 3150
telemt_connections_me_current 3150
telemt_handshake_timeouts_total 44212
telemt_upstream_connect_attempt_total 7218
telemt_upstream_connect_success_total 7218
telemt_upstream_connect_attempts_per_request{bucket="1"} 7218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6762
telemt_me_reconnect_success_total 5428
telemt_me_reader_eof_total 5764
telemt_me_idle_close_by_peer_total 5764
telemt_me_route_drop_no_conn_total 399498
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 825266
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4909
telemt_desync_full_logged_total 1627
telemt_desync_suppressed_total 3282
telemt_desync_frames_bucket_total{bucket="1_2"} 983
telemt_desync_frames_bucket_total{bucket="3_10"} 1880
telemt_desync_frames_bucket_total{bucket="gt_10"} 2046
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5529
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5413
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 824337
telemt_user_connections_current{user="hello"} 3150
telemt_user_octets_from_client{user="hello"} 12133443176 (11.30 GB)
telemt_user_octets_to_client{user="hello"} 446619474796 (415.95 GB)
telemt_user_unique_ips_current{user="hello"} 971
telemt_user_unique_ips_recent_window{user="hello"} 441
```