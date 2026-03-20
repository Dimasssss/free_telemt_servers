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

# Server Metrics 2026-03-20 08:23:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 54376.3 (15h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1193666
telemt_connections_bad_total 65343
telemt_connections_current 1878
telemt_connections_me_current 1878
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31780
telemt_upstream_connect_attempt_total 10461
telemt_upstream_connect_success_total 10348
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 10461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6576
telemt_me_reconnect_success_total 6526
telemt_me_reader_eof_total 6900
telemt_me_idle_close_by_peer_total 6898
telemt_me_route_drop_no_conn_total 348889
telemt_me_route_drop_channel_closed_total 174
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 985904
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4996
telemt_desync_full_logged_total 1790
telemt_desync_suppressed_total 3206
telemt_desync_frames_bucket_total{bucket="1_2"} 1023
telemt_desync_frames_bucket_total{bucket="3_10"} 1942
telemt_desync_frames_bucket_total{bucket="gt_10"} 2031
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 88
telemt_me_writer_removed_unexpected_total 6595
telemt_me_writer_restored_same_endpoint_total 6513
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 985443
telemt_user_connections_current{user="hello"} 1878
telemt_user_octets_from_client{user="hello"} 38175281852 (35.55 GB)
telemt_user_octets_to_client{user="hello"} 336409560453 (313.31 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 70832.0 (19h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5242239
telemt_connections_bad_total 465880
telemt_connections_current 3901
telemt_connections_me_current 3901
telemt_handshake_timeouts_total 110764
telemt_upstream_connect_attempt_total 13065
telemt_upstream_connect_success_total 12793
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 13065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12333
telemt_me_reconnect_success_total 8054
telemt_me_reader_eof_total 8620
telemt_me_idle_close_by_peer_total 8619
telemt_me_route_drop_no_conn_total 3164317
telemt_me_route_drop_channel_closed_total 55
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4325730
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16115
telemt_desync_full_logged_total 5332
telemt_desync_suppressed_total 10783
telemt_desync_frames_bucket_total{bucket="1_2"} 3220
telemt_desync_frames_bucket_total{bucket="3_10"} 6282
telemt_desync_frames_bucket_total{bucket="gt_10"} 6613
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 113
telemt_me_writer_removed_unexpected_total 8303
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7999
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 4327880
telemt_user_connections_current{user="hello"} 3901
telemt_user_octets_from_client{user="hello"} 57703130478 (53.74 GB)
telemt_user_octets_to_client{user="hello"} 1445991756846 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1344
telemt_user_unique_ips_recent_window{user="hello"} 511
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 4173.7 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217910
telemt_connections_bad_total 19116
telemt_connections_current 2709
telemt_connections_me_current 2709
telemt_handshake_timeouts_total 2246
telemt_upstream_connect_attempt_total 794
telemt_upstream_connect_success_total 794
telemt_upstream_connect_attempts_per_request{bucket="1"} 794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 506
telemt_me_reconnect_success_total 498
telemt_me_reader_eof_total 480
telemt_me_idle_close_by_peer_total 480
telemt_me_route_drop_no_conn_total 73186
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179135
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 810
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 378
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 481
telemt_me_writer_restored_same_endpoint_total 498
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 179381
telemt_user_connections_current{user="hello"} 2709
telemt_user_octets_from_client{user="hello"} 3082342136 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 70520056303 (65.68 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1010
telemt_user_unique_ips_recent_window{user="hello"} 404
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 70797.6 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6006172
telemt_connections_bad_total 309856
telemt_connections_current 5321
telemt_connections_me_current 5321
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 81716
telemt_upstream_connect_attempt_total 82722
telemt_upstream_connect_success_total 70981
telemt_upstream_connect_fail_total 11741
telemt_upstream_connect_attempts_per_request{bucket="1"} 82722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11516
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11741
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 11226
telemt_me_reconnect_success_total 8098
telemt_me_reader_eof_total 8436
telemt_me_idle_close_by_peer_total 8434
telemt_me_route_drop_no_conn_total 8164938
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5130952
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
telemt_desync_total 14098
telemt_desync_full_logged_total 4074
telemt_desync_suppressed_total 10024
telemt_desync_frames_bucket_total{bucket="1_2"} 3157
telemt_desync_frames_bucket_total{bucket="3_10"} 5635
telemt_desync_frames_bucket_total{bucket="gt_10"} 5306
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 830
telemt_me_writer_removed_unexpected_total 8933
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8094
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 835
telemt_user_connections_total{user="hello"} 5190188
telemt_user_connections_current{user="hello"} 5321
telemt_user_octets_from_client{user="hello"} 50502487299 (47.03 GB)
telemt_user_octets_to_client{user="hello"} 896250216777 (834.70 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1512
telemt_user_unique_ips_recent_window{user="hello"} 874
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 8381.1 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1755068
telemt_connections_bad_total 126451
telemt_connections_current 5883
telemt_connections_me_current 5883
telemt_handshake_timeouts_total 22234
telemt_upstream_connect_attempt_total 1466
telemt_upstream_connect_success_total 1457
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 990
telemt_me_reconnect_success_total 987
telemt_me_reader_eof_total 1002
telemt_me_idle_close_by_peer_total 1002
telemt_me_route_drop_no_conn_total 2720871
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1489691
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3238
telemt_desync_full_logged_total 949
telemt_desync_suppressed_total 2289
telemt_desync_frames_bucket_total{bucket="1_2"} 618
telemt_desync_frames_bucket_total{bucket="3_10"} 1301
telemt_desync_frames_bucket_total{bucket="gt_10"} 1319
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 990
telemt_me_writer_restored_same_endpoint_total 957
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 1485555
telemt_user_connections_current{user="hello"} 5883
telemt_user_octets_from_client{user="hello"} 14033499368 (13.07 GB)
telemt_user_octets_to_client{user="hello"} 201646893448 (187.80 GB)
telemt_user_unique_ips_current{user="hello"} 1822
telemt_user_unique_ips_recent_window{user="hello"} 981
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 8316.1 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129791
telemt_connections_bad_total 15571
telemt_connections_current 684
telemt_connections_me_current 684
telemt_handshake_timeouts_total 1608
telemt_upstream_connect_attempt_total 1488
telemt_upstream_connect_success_total 1475
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1015
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 1051
telemt_me_idle_close_by_peer_total 1051
telemt_me_route_drop_no_conn_total 67051
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122684
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 407
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 179
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 1020
telemt_me_writer_restored_same_endpoint_total 1000
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 105651
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 1531809748 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 41688267260 (38.83 GB)
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 70762.6 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3399202
telemt_connections_bad_total 223149
telemt_connections_current 5477
telemt_connections_me_current 5477
telemt_handshake_timeouts_total 64684
telemt_upstream_connect_attempt_total 12390
telemt_upstream_connect_success_total 12312
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 12390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8859
telemt_me_reconnect_success_total 8799
telemt_me_reader_eof_total 9308
telemt_me_idle_close_by_peer_total 9308
telemt_me_route_drop_no_conn_total 1164751
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2856466
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13987
telemt_desync_full_logged_total 4634
telemt_desync_suppressed_total 9353
telemt_desync_frames_bucket_total{bucket="1_2"} 2771
telemt_desync_frames_bucket_total{bucket="3_10"} 5023
telemt_desync_frames_bucket_total{bucket="gt_10"} 6193
telemt_pool_swap_total 72
telemt_me_writer_close_signal_drop_total 52
telemt_me_writer_removed_unexpected_total 8929
telemt_me_writer_restored_same_endpoint_total 8782
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 2854430
telemt_user_connections_current{user="hello"} 5477
telemt_user_octets_from_client{user="hello"} 60471276180 (56.32 GB)
telemt_user_octets_to_client{user="hello"} 1479350921216 (1.35 TB)
telemt_user_unique_ips_current{user="hello"} 1730
telemt_user_unique_ips_recent_window{user="hello"} 650
```