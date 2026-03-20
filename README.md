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

# Server Metrics 2026-03-20 09:04:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 56829.6 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1293393
telemt_connections_bad_total 70079
telemt_connections_current 1832
telemt_connections_me_current 1832
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 33670
telemt_upstream_connect_attempt_total 10915
telemt_upstream_connect_success_total 10801
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 10915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 6900
telemt_me_reconnect_success_total 6847
telemt_me_reader_eof_total 7244
telemt_me_idle_close_by_peer_total 7242
telemt_me_route_drop_no_conn_total 383999
telemt_me_route_drop_channel_closed_total 216
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1066925
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5458
telemt_desync_full_logged_total 1951
telemt_desync_suppressed_total 3507
telemt_desync_frames_bucket_total{bucket="1_2"} 1137
telemt_desync_frames_bucket_total{bucket="3_10"} 2114
telemt_desync_frames_bucket_total{bucket="gt_10"} 2207
telemt_pool_swap_total 60
telemt_me_writer_close_signal_drop_total 104
telemt_me_writer_removed_unexpected_total 6920
telemt_me_writer_restored_same_endpoint_total 6834
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1066475
telemt_user_connections_current{user="hello"} 1832
telemt_user_octets_from_client{user="hello"} 39377146164 (36.67 GB)
telemt_user_octets_to_client{user="hello"} 362216188477 (337.34 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 662
telemt_user_unique_ips_recent_window{user="hello"} 298
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 73285.4 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5491080
telemt_connections_bad_total 483100
telemt_connections_current 4534
telemt_connections_me_current 4534
telemt_handshake_timeouts_total 114404
telemt_upstream_connect_attempt_total 13498
telemt_upstream_connect_success_total 13209
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 13498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12617
telemt_me_reconnect_success_total 8334
telemt_me_reader_eof_total 8920
telemt_me_idle_close_by_peer_total 8919
telemt_me_route_drop_no_conn_total 3354776
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4527561
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16704
telemt_desync_full_logged_total 5589
telemt_desync_suppressed_total 11115
telemt_desync_frames_bucket_total{bucket="1_2"} 3325
telemt_desync_frames_bucket_total{bucket="3_10"} 6535
telemt_desync_frames_bucket_total{bucket="gt_10"} 6844
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 589
telemt_me_writer_close_signal_drop_total 120
telemt_me_writer_removed_unexpected_total 8588
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8279
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 4529818
telemt_user_connections_current{user="hello"} 4534
telemt_user_octets_from_client{user="hello"} 61458138290 (57.24 GB)
telemt_user_octets_to_client{user="hello"} 1507615819886 (1.37 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1549
telemt_user_unique_ips_recent_window{user="hello"} 740
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 6627.5 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389747
telemt_connections_bad_total 30832
telemt_connections_current 3062
telemt_connections_me_current 3062
telemt_handshake_timeouts_total 4431
telemt_upstream_connect_attempt_total 1375
telemt_upstream_connect_success_total 1375
telemt_upstream_connect_attempts_per_request{bucket="1"} 1375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 954
telemt_me_reconnect_success_total 941
telemt_me_reader_eof_total 939
telemt_me_idle_close_by_peer_total 939
telemt_me_route_drop_no_conn_total 134160
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321152
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1447
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 961
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 494
telemt_desync_frames_bucket_total{bucket="gt_10"} 677
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 929
telemt_me_writer_restored_same_endpoint_total 941
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 321393
telemt_user_connections_current{user="hello"} 3062
telemt_user_octets_from_client{user="hello"} 5264506552 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 127208732311 (118.47 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1124
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 73263.0 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4978640
telemt_connections_bad_total 598585
telemt_connections_current 5579
telemt_connections_me_current 5579
telemt_handshake_timeouts_total 73356
telemt_upstream_connect_attempt_total 13157
telemt_upstream_connect_success_total 13047
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 13157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6023
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3102
telemt_me_reconnect_attempts_total 8900
telemt_me_reconnect_success_total 7931
telemt_me_reader_eof_total 8314
telemt_me_idle_close_by_peer_total 8309
telemt_me_route_drop_no_conn_total 3045486
telemt_me_route_drop_channel_closed_total 312
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3605032
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12454
telemt_desync_full_logged_total 3981
telemt_desync_suppressed_total 8473
telemt_desync_frames_bucket_total{bucket="1_2"} 2923
telemt_desync_frames_bucket_total{bucket="3_10"} 4679
telemt_desync_frames_bucket_total{bucket="gt_10"} 4852
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 373
telemt_me_writer_removed_unexpected_total 8038
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7930
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 3611389
telemt_user_connections_current{user="hello"} 5579
telemt_user_octets_from_client{user="hello"} 55502138274 (51.69 GB)
telemt_user_octets_to_client{user="hello"} 1346947596216 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1753
telemt_user_unique_ips_recent_window{user="hello"} 809
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 73251.5 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6821337
telemt_connections_bad_total 323685
telemt_connections_current 5631
telemt_connections_me_current 5631
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 91686
telemt_upstream_connect_attempt_total 83136
telemt_upstream_connect_success_total 71372
telemt_upstream_connect_fail_total 11764
telemt_upstream_connect_attempts_per_request{bucket="1"} 83136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11764
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 11498
telemt_me_reconnect_success_total 8351
telemt_me_reader_eof_total 8706
telemt_me_idle_close_by_peer_total 8704
telemt_me_route_drop_no_conn_total 10056142
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5877279
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
telemt_desync_total 14971
telemt_desync_full_logged_total 4323
telemt_desync_suppressed_total 10648
telemt_desync_frames_bucket_total{bucket="1_2"} 3328
telemt_desync_frames_bucket_total{bucket="3_10"} 5995
telemt_desync_frames_bucket_total{bucket="gt_10"} 5648
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 842
telemt_me_writer_removed_unexpected_total 9200
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8347
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 849
telemt_user_connections_total{user="hello"} 5936719
telemt_user_connections_current{user="hello"} 5631
telemt_user_octets_from_client{user="hello"} 53592963135 (49.91 GB)
telemt_user_octets_to_client{user="hello"} 925551194493 (861.99 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1618
telemt_user_unique_ips_recent_window{user="hello"} 1033
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 10834.4 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2368363
telemt_connections_bad_total 169913
telemt_connections_current 6325
telemt_connections_me_current 6325
telemt_handshake_timeouts_total 28236
telemt_upstream_connect_attempt_total 1818
telemt_upstream_connect_success_total 1806
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 1244
telemt_me_reconnect_success_total 1241
telemt_me_reader_eof_total 1270
telemt_me_idle_close_by_peer_total 1269
telemt_me_route_drop_no_conn_total 3703794
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2021001
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4267
telemt_desync_full_logged_total 1234
telemt_desync_suppressed_total 3033
telemt_desync_frames_bucket_total{bucket="1_2"} 791
telemt_desync_frames_bucket_total{bucket="3_10"} 1754
telemt_desync_frames_bucket_total{bucket="gt_10"} 1722
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 1248
telemt_me_writer_restored_same_endpoint_total 1211
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 2015805
telemt_user_connections_current{user="hello"} 6325
telemt_user_octets_from_client{user="hello"} 17256144900 (16.07 GB)
telemt_user_octets_to_client{user="hello"} 258606006752 (240.85 GB)
telemt_user_unique_ips_current{user="hello"} 1945
telemt_user_unique_ips_recent_window{user="hello"} 887
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 412.0 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14246
telemt_connections_bad_total 3780
telemt_connections_current 694
telemt_connections_me_current 694
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 1621
telemt_upstream_connect_success_total 1619
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 181
telemt_me_reconnect_success_total 179
telemt_me_reader_eof_total 107
telemt_me_idle_close_by_peer_total 107
telemt_me_route_drop_no_conn_total 3087
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8333
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_me_writer_close_signal_drop_total 20
telemt_me_writer_removed_unexpected_total 126
telemt_me_writer_restored_same_endpoint_total 177
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 9849
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 92321083 (88.04 MB)
telemt_user_octets_to_client{user="hello"} 1193497092 (1.11 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 73216.1 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3713268
telemt_connections_bad_total 240909
telemt_connections_current 5793
telemt_connections_me_current 5793
telemt_handshake_timeouts_total 76689
telemt_upstream_connect_attempt_total 12845
telemt_upstream_connect_success_total 12764
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 12845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9175
telemt_me_reconnect_success_total 9109
telemt_me_reader_eof_total 9628
telemt_me_idle_close_by_peer_total 9628
telemt_me_route_drop_no_conn_total 1331978
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3127662
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14931
telemt_desync_full_logged_total 4986
telemt_desync_suppressed_total 9945
telemt_desync_frames_bucket_total{bucket="1_2"} 2964
telemt_desync_frames_bucket_total{bucket="3_10"} 5391
telemt_desync_frames_bucket_total{bucket="gt_10"} 6576
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 55
telemt_me_writer_removed_unexpected_total 9246
telemt_me_writer_restored_same_endpoint_total 9092
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 3125639
telemt_user_connections_current{user="hello"} 5793
telemt_user_octets_from_client{user="hello"} 64451201516 (60.02 GB)
telemt_user_octets_to_client{user="hello"} 1596050591924 (1.45 TB)
telemt_user_unique_ips_current{user="hello"} 1909
telemt_user_unique_ips_recent_window{user="hello"} 796
```