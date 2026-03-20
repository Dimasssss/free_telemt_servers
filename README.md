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

# Server Metrics 2026-03-20 10:01:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 60203.9 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1509410
telemt_connections_bad_total 75134
telemt_connections_current 3967
telemt_connections_me_current 3967
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 37691
telemt_upstream_connect_attempt_total 11436
telemt_upstream_connect_success_total 11317
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 11436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 7284
telemt_me_reconnect_success_total 7229
telemt_me_reader_eof_total 7654
telemt_me_idle_close_by_peer_total 7652
telemt_me_route_drop_no_conn_total 468388
telemt_me_route_drop_channel_closed_total 317
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1207310
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6327
telemt_desync_full_logged_total 2227
telemt_desync_suppressed_total 4100
telemt_desync_frames_bucket_total{bucket="1_2"} 1376
telemt_desync_frames_bucket_total{bucket="3_10"} 2437
telemt_desync_frames_bucket_total{bucket="gt_10"} 2514
telemt_pool_swap_total 62
telemt_me_writer_close_signal_drop_total 161
telemt_me_writer_removed_unexpected_total 7311
telemt_me_writer_restored_same_endpoint_total 7216
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1248518
telemt_user_connections_current{user="hello"} 3967
telemt_user_octets_from_client{user="hello"} 41817893972 (38.95 GB)
telemt_user_octets_to_client{user="hello"} 396485572997 (369.26 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 796
telemt_user_unique_ips_recent_window{user="hello"} 679
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 76659.6 (21h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5857017
telemt_connections_bad_total 518575
telemt_connections_current 4313
telemt_connections_me_current 4313
telemt_handshake_timeouts_total 120237
telemt_upstream_connect_attempt_total 14169
telemt_upstream_connect_success_total 13866
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 14169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 14956
telemt_me_reconnect_success_total 8814
telemt_me_reader_eof_total 9461
telemt_me_idle_close_by_peer_total 9460
telemt_me_route_drop_no_conn_total 3616616
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4817036
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17695
telemt_desync_full_logged_total 5949
telemt_desync_suppressed_total 11746
telemt_desync_frames_bucket_total{bucket="1_2"} 3522
telemt_desync_frames_bucket_total{bucket="3_10"} 6938
telemt_desync_frames_bucket_total{bucket="gt_10"} 7235
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 3438
telemt_me_writer_close_signal_drop_total 132
telemt_me_writer_removed_unexpected_total 9131
telemt_me_refill_failed_total 189
telemt_me_writer_restored_same_endpoint_total 8759
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 317
telemt_user_connections_total{user="hello"} 4818509
telemt_user_connections_current{user="hello"} 4313
telemt_user_octets_from_client{user="hello"} 65051754166 (60.58 GB)
telemt_user_octets_to_client{user="hello"} 1592171028018 (1.45 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1508
telemt_user_unique_ips_recent_window{user="hello"} 696
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 10001.0 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672259
telemt_connections_bad_total 67009
telemt_connections_current 3389
telemt_connections_me_current 3389
telemt_handshake_timeouts_total 7292
telemt_upstream_connect_attempt_total 1835
telemt_upstream_connect_success_total 1835
telemt_upstream_connect_attempts_per_request{bucket="1"} 1835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1247
telemt_me_reconnect_success_total 1234
telemt_me_reader_eof_total 1251
telemt_me_idle_close_by_peer_total 1251
telemt_me_route_drop_no_conn_total 265012
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539641
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2139
telemt_desync_full_logged_total 711
telemt_desync_suppressed_total 1428
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 740
telemt_desync_frames_bucket_total{bucket="gt_10"} 972
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1229
telemt_me_writer_restored_same_endpoint_total 1234
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 539881
telemt_user_connections_current{user="hello"} 3389
telemt_user_octets_from_client{user="hello"} 8632654772 (8.04 GB)
telemt_user_octets_to_client{user="hello"} 204136546271 (190.12 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1311
telemt_user_unique_ips_recent_window{user="hello"} 586
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 76637.0 (21h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5699948
telemt_connections_bad_total 650505
telemt_connections_current 5338
telemt_connections_me_current 5338
telemt_handshake_timeouts_total 84683
telemt_upstream_connect_attempt_total 19868
telemt_upstream_connect_success_total 14808
telemt_upstream_connect_fail_total 5060
telemt_upstream_connect_attempts_per_request{bucket="1"} 19868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 911
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5060
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 3102
telemt_me_reconnect_attempts_total 9212
telemt_me_reconnect_success_total 8219
telemt_me_reader_eof_total 8625
telemt_me_idle_close_by_peer_total 8620
telemt_me_route_drop_no_conn_total 3769544
telemt_me_route_drop_channel_closed_total 410
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4142016
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 180
telemt_me_endpoint_quarantine_total 3
telemt_me_kdf_drift_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13509
telemt_desync_full_logged_total 4326
telemt_desync_suppressed_total 9183
telemt_desync_frames_bucket_total{bucket="1_2"} 3126
telemt_desync_frames_bucket_total{bucket="3_10"} 5062
telemt_desync_frames_bucket_total{bucket="gt_10"} 5321
telemt_pool_swap_total 74
telemt_me_writer_close_signal_drop_total 445
telemt_me_writer_removed_unexpected_total 8348
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 8218
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 4221369
telemt_user_connections_current{user="hello"} 5338
telemt_user_octets_from_client{user="hello"} 60189996831 (56.06 GB)
telemt_user_octets_to_client{user="hello"} 1463689244284 (1.33 TB)
telemt_user_msgs_from_client{user="hello"} 5696
telemt_user_msgs_to_client{user="hello"} 6360
telemt_user_unique_ips_current{user="hello"} 1679
telemt_user_unique_ips_recent_window{user="hello"} 829
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 76625.1 (21h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8099673
telemt_connections_bad_total 353821
telemt_connections_current 6268
telemt_connections_me_current 6268
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 103015
telemt_upstream_connect_attempt_total 83656
telemt_upstream_connect_success_total 71862
telemt_upstream_connect_fail_total 11794
telemt_upstream_connect_attempts_per_request{bucket="1"} 83656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11794
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 222
telemt_me_reconnect_attempts_total 11829
telemt_me_reconnect_success_total 8665
telemt_me_reader_eof_total 9046
telemt_me_idle_close_by_peer_total 9044
telemt_me_route_drop_no_conn_total 12978752
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7039912
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
telemt_desync_total 16063
telemt_desync_full_logged_total 4702
telemt_desync_suppressed_total 11361
telemt_desync_frames_bucket_total{bucket="1_2"} 3550
telemt_desync_frames_bucket_total{bucket="3_10"} 6442
telemt_desync_frames_bucket_total{bucket="gt_10"} 6071
telemt_pool_swap_total 60
telemt_me_writer_close_signal_drop_total 855
telemt_me_writer_removed_unexpected_total 9531
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8661
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 866
telemt_user_connections_total{user="hello"} 7099014
telemt_user_connections_current{user="hello"} 6268
telemt_user_octets_from_client{user="hello"} 57952926179 (53.97 GB)
telemt_user_octets_to_client{user="hello"} 963557115345 (897.38 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1805
telemt_user_unique_ips_recent_window{user="hello"} 1346
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 14208.2 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3171065
telemt_connections_bad_total 248005
telemt_connections_current 6813
telemt_connections_me_current 6813
telemt_handshake_timeouts_total 37123
telemt_upstream_connect_attempt_total 2373
telemt_upstream_connect_success_total 2360
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 1626
telemt_me_reconnect_success_total 1617
telemt_me_reader_eof_total 1666
telemt_me_idle_close_by_peer_total 1665
telemt_me_route_drop_no_conn_total 4805481
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2681701
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5874
telemt_desync_full_logged_total 1691
telemt_desync_suppressed_total 4183
telemt_desync_frames_bucket_total{bucket="1_2"} 1089
telemt_desync_frames_bucket_total{bucket="3_10"} 2417
telemt_desync_frames_bucket_total{bucket="gt_10"} 2368
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 47
telemt_me_writer_removed_unexpected_total 1634
telemt_me_writer_restored_same_endpoint_total 1587
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 2676476
telemt_user_connections_current{user="hello"} 6813
telemt_user_octets_from_client{user="hello"} 23599411836 (21.98 GB)
telemt_user_octets_to_client{user="hello"} 337872452012 (314.67 GB)
telemt_user_unique_ips_current{user="hello"} 2098
telemt_user_unique_ips_recent_window{user="hello"} 1165
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 3786.9 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88821
telemt_connections_bad_total 20576
telemt_connections_current 895
telemt_connections_me_current 895
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 1551
telemt_upstream_connect_attempt_total 2250
telemt_upstream_connect_success_total 2229
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 2250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 619
telemt_me_reconnect_success_total 615
telemt_me_reader_eof_total 587
telemt_me_idle_close_by_peer_total 587
telemt_me_route_drop_no_conn_total 26804
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61924
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 139
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 582
telemt_me_writer_restored_same_endpoint_total 613
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 63442
telemt_user_connections_current{user="hello"} 895
telemt_user_octets_from_client{user="hello"} 1078054203 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 11193189652 (10.42 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 76589.5 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4130377
telemt_connections_bad_total 257153
telemt_connections_current 6486
telemt_connections_me_current 6486
telemt_handshake_timeouts_total 94724
telemt_upstream_connect_attempt_total 13333
telemt_upstream_connect_success_total 13249
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 13333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9499
telemt_me_reconnect_success_total 9431
telemt_me_reader_eof_total 9980
telemt_me_idle_close_by_peer_total 9979
telemt_me_route_drop_no_conn_total 1485879
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3488886
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16634
telemt_desync_full_logged_total 5519
telemt_desync_suppressed_total 11115
telemt_desync_frames_bucket_total{bucket="1_2"} 3491
telemt_desync_frames_bucket_total{bucket="3_10"} 5998
telemt_desync_frames_bucket_total{bucket="gt_10"} 7145
telemt_pool_swap_total 76
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 9577
telemt_me_writer_restored_same_endpoint_total 9414
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 3486795
telemt_user_connections_current{user="hello"} 6486
telemt_user_octets_from_client{user="hello"} 75644545860 (70.45 GB)
telemt_user_octets_to_client{user="hello"} 1749639667644 (1.59 TB)
telemt_user_unique_ips_current{user="hello"} 2061
telemt_user_unique_ips_recent_window{user="hello"} 877
```