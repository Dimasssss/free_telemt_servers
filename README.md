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

# Server Metrics 2026-03-19 23:21:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 21828.2 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459754
telemt_connections_bad_total 29070
telemt_connections_current 831
telemt_connections_me_current 831
telemt_handshake_timeouts_total 7047
telemt_upstream_connect_attempt_total 3647
telemt_upstream_connect_success_total 3616
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 3647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2515
telemt_me_reconnect_success_total 2496
telemt_me_reader_eof_total 2651
telemt_me_idle_close_by_peer_total 2651
telemt_me_route_drop_no_conn_total 136165
telemt_me_route_drop_channel_closed_total 51
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364700
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1947
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 406
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 904
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2548
telemt_me_writer_restored_same_endpoint_total 2483
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 364972
telemt_user_connections_current{user="hello"} 831
telemt_user_octets_from_client{user="hello"} 22052786608 (20.54 GB)
telemt_user_octets_to_client{user="hello"} 134695004380 (125.44 GB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 38283.4 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2860023
telemt_connections_bad_total 122813
telemt_connections_current 1465
telemt_connections_me_current 1465
telemt_handshake_timeouts_total 58590
telemt_upstream_connect_attempt_total 7692
telemt_upstream_connect_success_total 7569
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 7692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8652
telemt_me_reconnect_success_total 4417
telemt_me_reader_eof_total 4737
telemt_me_idle_close_by_peer_total 4737
telemt_me_route_drop_no_conn_total 1464117
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2444479
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10718
telemt_desync_full_logged_total 3532
telemt_desync_suppressed_total 7186
telemt_desync_frames_bucket_total{bucket="1_2"} 2007
telemt_desync_frames_bucket_total{bucket="3_10"} 4201
telemt_desync_frames_bucket_total{bucket="gt_10"} 4510
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 4596
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4362
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 2444308
telemt_user_connections_current{user="hello"} 1465
telemt_user_octets_from_client{user="hello"} 38212955042 (35.59 GB)
telemt_user_octets_to_client{user="hello"} 883044440462 (822.40 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 659
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 38261.6 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2781300
telemt_connections_bad_total 464339
telemt_connections_current 1172
telemt_connections_me_current 1172
telemt_handshake_timeouts_total 36826
telemt_upstream_connect_attempt_total 6053
telemt_upstream_connect_success_total 6005
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 6053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5010
telemt_me_reconnect_success_total 4080
telemt_me_reader_eof_total 4258
telemt_me_idle_close_by_peer_total 4257
telemt_me_route_drop_no_conn_total 1883094
telemt_me_route_drop_channel_closed_total 169
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1936511
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7510
telemt_desync_full_logged_total 2267
telemt_desync_suppressed_total 5243
telemt_desync_frames_bucket_total{bucket="1_2"} 1848
telemt_desync_frames_bucket_total{bucket="3_10"} 2859
telemt_desync_frames_bucket_total{bucket="gt_10"} 2803
telemt_pool_swap_total 36
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 4115
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4079
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 1932303
telemt_user_connections_current{user="hello"} 1172
telemt_user_octets_from_client{user="hello"} 29031944160 (27.04 GB)
telemt_user_octets_to_client{user="hello"} 732355200196 (682.06 GB)
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 38249.4 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2426365
telemt_connections_bad_total 100195
telemt_connections_current 1135
telemt_connections_me_current 1135
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 29833
telemt_upstream_connect_attempt_total 53004
telemt_upstream_connect_success_total 48852
telemt_upstream_connect_fail_total 4152
telemt_upstream_connect_attempts_per_request{bucket="1"} 53004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 513
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4152
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7358
telemt_me_reconnect_success_total 4610
telemt_me_reader_eof_total 4775
telemt_me_idle_close_by_peer_total 4774
telemt_me_route_drop_no_conn_total 1838627
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2046022
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8142
telemt_desync_full_logged_total 2568
telemt_desync_suppressed_total 5574
telemt_desync_frames_bucket_total{bucket="1_2"} 1993
telemt_desync_frames_bucket_total{bucket="3_10"} 2961
telemt_desync_frames_bucket_total{bucket="gt_10"} 3188
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 403
telemt_me_writer_removed_unexpected_total 5174
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4606
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 564
telemt_user_connections_total{user="hello"} 2087178
telemt_user_connections_current{user="hello"} 1135
telemt_user_octets_from_client{user="hello"} 34102467567 (31.76 GB)
telemt_user_octets_to_client{user="hello"} 560758703707 (522.25 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 91972.8 (25h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6137440
telemt_connections_bad_total 1037197
telemt_connections_current 1309
telemt_connections_me_current 1309
telemt_relay_adaptive_promotions_total 27
telemt_relay_adaptive_demotions_total 3535
telemt_relay_adaptive_hard_promotions_total 25
telemt_handshake_timeouts_total 110404
telemt_upstream_connect_attempt_total 116724
telemt_upstream_connect_success_total 85399
telemt_upstream_connect_fail_total 31325
telemt_upstream_connect_attempts_per_request{bucket="1"} 116724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31325
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77312
telemt_me_reconnect_success_total 11775
telemt_me_reader_eof_total 12554
telemt_me_idle_close_by_peer_total 12543
telemt_me_route_drop_no_conn_total 2763822
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4334286
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
telemt_desync_total 19072
telemt_desync_full_logged_total 5965
telemt_desync_suppressed_total 13107
telemt_desync_frames_bucket_total{bucket="1_2"} 3332
telemt_desync_frames_bucket_total{bucket="3_10"} 7827
telemt_desync_frames_bucket_total{bucket="gt_10"} 7913
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 12062
telemt_me_refill_failed_total 2043
telemt_me_writer_restored_same_endpoint_total 11750
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 4402195
telemt_user_connections_current{user="hello"} 1309
telemt_user_octets_from_client{user="hello"} 67887790778 (63.23 GB)
telemt_user_octets_to_client{user="hello"} 1705876634988 (1.55 TB)
telemt_user_msgs_from_client{user="hello"} 702760
telemt_user_msgs_to_client{user="hello"} 2862853
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 38212.8 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 668976
telemt_connections_bad_total 67436
telemt_connections_current 347
telemt_connections_me_current 347
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12811
telemt_upstream_connect_attempt_total 11318
telemt_upstream_connect_success_total 11019
telemt_upstream_connect_fail_total 299
telemt_upstream_connect_attempts_per_request{bucket="1"} 11318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5900
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 626
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 299
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5261
telemt_me_reconnect_success_total 5162
telemt_me_reader_eof_total 5383
telemt_me_idle_close_by_peer_total 5381
telemt_me_route_drop_no_conn_total 454192
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 552468
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
telemt_desync_total 1380
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 32
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5207
telemt_me_writer_restored_same_endpoint_total 5153
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 540092
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 7053914686 (6.57 GB)
telemt_user_octets_to_client{user="hello"} 130163098398 (121.22 GB)
telemt_user_msgs_from_client{user="hello"} 10105
telemt_user_msgs_to_client{user="hello"} 15806
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 38214.0 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1929534
telemt_connections_bad_total 117041
telemt_connections_current 1244
telemt_connections_me_current 1244
telemt_handshake_timeouts_total 35757
telemt_upstream_connect_attempt_total 6594
telemt_upstream_connect_success_total 6543
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 6594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4647
telemt_me_reconnect_success_total 4610
telemt_me_reader_eof_total 4861
telemt_me_idle_close_by_peer_total 4861
telemt_me_route_drop_no_conn_total 716390
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1663307
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8853
telemt_desync_full_logged_total 2820
telemt_desync_suppressed_total 6033
telemt_desync_frames_bucket_total{bucket="1_2"} 1621
telemt_desync_frames_bucket_total{bucket="3_10"} 3108
telemt_desync_frames_bucket_total{bucket="gt_10"} 4124
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4686
telemt_me_writer_restored_same_endpoint_total 4593
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1662444
telemt_user_connections_current{user="hello"} 1244
telemt_user_octets_from_client{user="hello"} 28193001640 (26.26 GB)
telemt_user_octets_to_client{user="hello"} 840549606240 (782.82 GB)
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 113
```