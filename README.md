# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

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
Этот сервер пользуется большим спросом. Я арендовал еще один такой же, чтобы распределить нагрузку.

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

# Server Metrics 2026-03-20 10:06:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 60510.0 (16h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1627027
telemt_connections_bad_total 76632
telemt_connections_current 3999
telemt_connections_me_current 3999
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 38501
telemt_upstream_connect_attempt_total 11496
telemt_upstream_connect_success_total 11376
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 11496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1310
telemt_me_reconnect_attempts_total 7308
telemt_me_reconnect_success_total 7252
telemt_me_reader_eof_total 7680
telemt_me_idle_close_by_peer_total 7677
telemt_me_route_drop_no_conn_total 472032
telemt_me_route_drop_channel_closed_total 338
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1235380
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6341
telemt_desync_full_logged_total 2232
telemt_desync_suppressed_total 4109
telemt_desync_frames_bucket_total{bucket="1_2"} 1381
telemt_desync_frames_bucket_total{bucket="3_10"} 2446
telemt_desync_frames_bucket_total{bucket="gt_10"} 2514
telemt_pool_swap_total 62
telemt_me_writer_close_signal_drop_total 188
telemt_me_writer_removed_unexpected_total 7336
telemt_me_writer_restored_same_endpoint_total 7239
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 1360443
telemt_user_connections_current{user="hello"} 3999
telemt_user_octets_from_client{user="hello"} 42458269980 (39.54 GB)
telemt_user_octets_to_client{user="hello"} 396485581653 (369.26 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 770
telemt_user_unique_ips_recent_window{user="hello"} 663
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 76966.1 (21h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5892331
telemt_connections_bad_total 521016
telemt_connections_current 4179
telemt_connections_me_current 4179
telemt_handshake_timeouts_total 120633
telemt_upstream_connect_attempt_total 14206
telemt_upstream_connect_success_total 13903
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 14206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 15697
telemt_me_reconnect_success_total 8851
telemt_me_reader_eof_total 9519
telemt_me_idle_close_by_peer_total 9518
telemt_me_route_drop_no_conn_total 3654287
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4846311
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17808
telemt_desync_full_logged_total 5983
telemt_desync_suppressed_total 11825
telemt_desync_frames_bucket_total{bucket="1_2"} 3546
telemt_desync_frames_bucket_total{bucket="3_10"} 6973
telemt_desync_frames_bucket_total{bucket="gt_10"} 7289
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 3438
telemt_me_writer_close_signal_drop_total 136
telemt_me_writer_removed_unexpected_total 9190
telemt_me_refill_failed_total 211
telemt_me_writer_restored_same_endpoint_total 8796
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 4847791
telemt_user_connections_current{user="hello"} 4179
telemt_user_octets_from_client{user="hello"} 65489651006 (60.99 GB)
telemt_user_octets_to_client{user="hello"} 1601436819458 (1.46 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1537
telemt_user_unique_ips_recent_window{user="hello"} 602
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 10307.7 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 701594
telemt_connections_bad_total 68830
telemt_connections_current 3386
telemt_connections_me_current 3386
telemt_handshake_timeouts_total 7674
telemt_upstream_connect_attempt_total 1892
telemt_upstream_connect_success_total 1892
telemt_upstream_connect_attempts_per_request{bucket="1"} 1892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1297
telemt_me_reconnect_success_total 1281
telemt_me_reader_eof_total 1303
telemt_me_idle_close_by_peer_total 1303
telemt_me_route_drop_no_conn_total 299041
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564396
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2252
telemt_desync_full_logged_total 742
telemt_desync_suppressed_total 1510
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 780
telemt_desync_frames_bucket_total{bucket="gt_10"} 1016
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1276
telemt_me_writer_restored_same_endpoint_total 1281
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 564638
telemt_user_connections_current{user="hello"} 3386
telemt_user_octets_from_client{user="hello"} 8975204496 (8.36 GB)
telemt_user_octets_to_client{user="hello"} 212212848727 (197.64 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1300
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 76931.3 (21h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8228176
telemt_connections_bad_total 358276
telemt_connections_current 6379
telemt_connections_me_current 6379
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 103956
telemt_upstream_connect_attempt_total 83686
telemt_upstream_connect_success_total 71890
telemt_upstream_connect_fail_total 11796
telemt_upstream_connect_attempts_per_request{bucket="1"} 83686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11796
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 11859
telemt_me_reconnect_success_total 8693
telemt_me_reader_eof_total 9080
telemt_me_idle_close_by_peer_total 9078
telemt_me_route_drop_no_conn_total 13252973
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7156670
telemt_me_writer_pick_total{mode="p2c",result="full"} 4273
telemt_me_writer_pick_total{mode="p2c",result="closed"} 804
telemt_me_writer_pick_blocking_fallback_total 5052
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16158
telemt_desync_full_logged_total 4729
telemt_desync_suppressed_total 11429
telemt_desync_frames_bucket_total{bucket="1_2"} 3562
telemt_desync_frames_bucket_total{bucket="3_10"} 6496
telemt_desync_frames_bucket_total{bucket="gt_10"} 6100
telemt_pool_swap_total 60
telemt_me_writer_close_signal_drop_total 856
telemt_me_writer_removed_unexpected_total 9562
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8689
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 869
telemt_user_connections_total{user="hello"} 7215761
telemt_user_connections_current{user="hello"} 6379
telemt_user_octets_from_client{user="hello"} 58394105407 (54.38 GB)
telemt_user_octets_to_client{user="hello"} 967319611933 (900.89 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1809
telemt_user_unique_ips_recent_window{user="hello"} 1189
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 14514.7 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3296231
telemt_connections_bad_total 251501
telemt_connections_current 7208
telemt_connections_me_current 7208
telemt_handshake_timeouts_total 37922
telemt_upstream_connect_attempt_total 2446
telemt_upstream_connect_success_total 2432
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 213
telemt_me_reconnect_attempts_total 1655
telemt_me_reconnect_success_total 1646
telemt_me_reader_eof_total 1697
telemt_me_idle_close_by_peer_total 1696
telemt_me_route_drop_no_conn_total 5015845
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2796626
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6030
telemt_desync_full_logged_total 1730
telemt_desync_suppressed_total 4300
telemt_desync_frames_bucket_total{bucket="1_2"} 1104
telemt_desync_frames_bucket_total{bucket="3_10"} 2496
telemt_desync_frames_bucket_total{bucket="gt_10"} 2430
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 47
telemt_me_writer_removed_unexpected_total 1665
telemt_me_writer_restored_same_endpoint_total 1616
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2791368
telemt_user_connections_current{user="hello"} 7208
telemt_user_octets_from_client{user="hello"} 24205610588 (22.54 GB)
telemt_user_octets_to_client{user="hello"} 344416510908 (320.76 GB)
telemt_user_unique_ips_current{user="hello"} 2159
telemt_user_unique_ips_recent_window{user="hello"} 1302
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 4091.7 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97342
telemt_connections_bad_total 23452
telemt_connections_current 905
telemt_connections_me_current 905
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 1592
telemt_upstream_connect_attempt_total 2287
telemt_upstream_connect_success_total 2266
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 2287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 467
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 656
telemt_me_reconnect_success_total 652
telemt_me_reader_eof_total 625
telemt_me_idle_close_by_peer_total 625
telemt_me_route_drop_no_conn_total 31717
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67359
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 164
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 620
telemt_me_writer_restored_same_endpoint_total 650
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 68877
telemt_user_connections_current{user="hello"} 905
telemt_user_octets_from_client{user="hello"} 1134230151 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 12453941596 (11.60 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 76896.3 (21h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4189348
telemt_connections_bad_total 274350
telemt_connections_current 6675
telemt_connections_me_current 6675
telemt_handshake_timeouts_total 96236
telemt_upstream_connect_attempt_total 13422
telemt_upstream_connect_success_total 13338
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 13422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9575
telemt_me_reconnect_success_total 9506
telemt_me_reader_eof_total 10055
telemt_me_idle_close_by_peer_total 10054
telemt_me_route_drop_no_conn_total 1517436
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3526618
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16826
telemt_desync_full_logged_total 5572
telemt_desync_suppressed_total 11254
telemt_desync_frames_bucket_total{bucket="1_2"} 3536
telemt_desync_frames_bucket_total{bucket="3_10"} 6076
telemt_desync_frames_bucket_total{bucket="gt_10"} 7214
telemt_pool_swap_total 76
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 9653
telemt_me_writer_restored_same_endpoint_total 9489
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 3524520
telemt_user_connections_current{user="hello"} 6675
telemt_user_octets_from_client{user="hello"} 76805708264 (71.53 GB)
telemt_user_octets_to_client{user="hello"} 1763269038968 (1.60 TB)
telemt_user_unique_ips_current{user="hello"} 2104
telemt_user_unique_ips_recent_window{user="hello"} 828
```