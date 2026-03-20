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

# Server Metrics 2026-03-20 07:32:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 51312.2 (14h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082331
telemt_connections_bad_total 63869
telemt_connections_current 1845
telemt_connections_me_current 1845
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 27654
telemt_upstream_connect_attempt_total 9899
telemt_upstream_connect_success_total 9790
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 9899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6195
telemt_me_reconnect_success_total 6149
telemt_me_reader_eof_total 6509
telemt_me_idle_close_by_peer_total 6508
telemt_me_route_drop_no_conn_total 312934
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 889230
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4503
telemt_desync_full_logged_total 1626
telemt_desync_suppressed_total 2877
telemt_desync_frames_bucket_total{bucket="1_2"} 904
telemt_desync_frames_bucket_total{bucket="3_10"} 1746
telemt_desync_frames_bucket_total{bucket="gt_10"} 1853
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 71
telemt_me_writer_removed_unexpected_total 6217
telemt_me_writer_restored_same_endpoint_total 6136
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 888659
telemt_user_connections_current{user="hello"} 1845
telemt_user_octets_from_client{user="hello"} 35619743708 (33.17 GB)
telemt_user_octets_to_client{user="hello"} 305748574733 (284.75 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 622
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 67768.1 (18h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4989516
telemt_connections_bad_total 443355
telemt_connections_current 3658
telemt_connections_me_current 3658
telemt_handshake_timeouts_total 104378
telemt_upstream_connect_attempt_total 12625
telemt_upstream_connect_success_total 12364
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 12625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12033
telemt_me_reconnect_success_total 7760
telemt_me_reader_eof_total 8307
telemt_me_idle_close_by_peer_total 8306
telemt_me_route_drop_no_conn_total 3080162
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4121120
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15285
telemt_desync_full_logged_total 5030
telemt_desync_suppressed_total 10255
telemt_desync_frames_bucket_total{bucket="1_2"} 3010
telemt_desync_frames_bucket_total{bucket="3_10"} 5968
telemt_desync_frames_bucket_total{bucket="gt_10"} 6307
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 109
telemt_me_writer_removed_unexpected_total 8003
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7705
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 4122930
telemt_user_connections_current{user="hello"} 3658
telemt_user_octets_from_client{user="hello"} 54916009230 (51.14 GB)
telemt_user_octets_to_client{user="hello"} 1367848904290 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1330
telemt_user_unique_ips_recent_window{user="hello"} 474
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 1109.7 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29234
telemt_connections_bad_total 2359
telemt_connections_current 1799
telemt_connections_me_current 1799
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 343
telemt_upstream_connect_success_total 343
telemt_upstream_connect_attempts_per_request{bucket="1"} 343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 185
telemt_me_reconnect_success_total 182
telemt_me_reader_eof_total 147
telemt_me_idle_close_by_peer_total 147
telemt_me_route_drop_no_conn_total 10091
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25181
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 164
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 162
telemt_me_writer_restored_same_endpoint_total 182
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 25249
telemt_user_connections_current{user="hello"} 1799
telemt_user_octets_from_client{user="hello"} 486863372 (464.31 MB)
telemt_user_octets_to_client{user="hello"} 7552613339 (7.03 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 671
telemt_user_unique_ips_recent_window{user="hello"} 330
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 67746.1 (18h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4283271
telemt_connections_bad_total 544491
telemt_connections_current 4242
telemt_connections_me_current 4242
telemt_handshake_timeouts_total 65410
telemt_upstream_connect_attempt_total 12430
telemt_upstream_connect_success_total 12324
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 12430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3086
telemt_me_reconnect_attempts_total 8442
telemt_me_reconnect_success_total 7478
telemt_me_reader_eof_total 7827
telemt_me_idle_close_by_peer_total 7822
telemt_me_route_drop_no_conn_total 2796178
telemt_me_route_drop_channel_closed_total 267
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3081365
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10874
telemt_desync_full_logged_total 3414
telemt_desync_suppressed_total 7460
telemt_desync_frames_bucket_total{bucket="1_2"} 2591
telemt_desync_frames_bucket_total{bucket="3_10"} 4157
telemt_desync_frames_bucket_total{bucket="gt_10"} 4126
telemt_pool_swap_total 67
telemt_me_writer_close_signal_drop_total 320
telemt_me_writer_removed_unexpected_total 7576
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7477
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 3087743
telemt_user_connections_current{user="hello"} 4242
telemt_user_octets_from_client{user="hello"} 43085844550 (40.13 GB)
telemt_user_octets_to_client{user="hello"} 1155539691800 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1411
telemt_user_unique_ips_recent_window{user="hello"} 572
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 67733.6 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4899050
telemt_connections_bad_total 293482
telemt_connections_current 5198
telemt_connections_me_current 5198
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 68475
telemt_upstream_connect_attempt_total 68304
telemt_upstream_connect_success_total 63559
telemt_upstream_connect_fail_total 4745
telemt_upstream_connect_attempts_per_request{bucket="1"} 68304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 713
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4745
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 10768
telemt_me_reconnect_success_total 7778
telemt_me_reader_eof_total 8124
telemt_me_idle_close_by_peer_total 8123
telemt_me_route_drop_no_conn_total 6076495
telemt_me_route_drop_channel_closed_total 79
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4133196
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13275
telemt_desync_full_logged_total 3836
telemt_desync_suppressed_total 9439
telemt_desync_frames_bucket_total{bucket="1_2"} 2967
telemt_desync_frames_bucket_total{bucket="3_10"} 5262
telemt_desync_frames_bucket_total{bucket="gt_10"} 5046
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 681
telemt_me_writer_removed_unexpected_total 8512
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7774
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 734
telemt_user_connections_total{user="hello"} 4184628
telemt_user_connections_current{user="hello"} 5198
telemt_user_octets_from_client{user="hello"} 47435970760 (44.18 GB)
telemt_user_octets_to_client{user="hello"} 862262836411 (803.04 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1519
telemt_user_unique_ips_recent_window{user="hello"} 829
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 5316.7 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 884083
telemt_connections_bad_total 77500
telemt_connections_current 5666
telemt_connections_me_current 5666
telemt_handshake_timeouts_total 15842
telemt_upstream_connect_attempt_total 840
telemt_upstream_connect_success_total 836
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 547
telemt_me_reconnect_success_total 545
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 1103764
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 736843
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2011
telemt_desync_full_logged_total 619
telemt_desync_suppressed_total 1392
telemt_desync_frames_bucket_total{bucket="1_2"} 403
telemt_desync_frames_bucket_total{bucket="3_10"} 814
telemt_desync_frames_bucket_total{bucket="gt_10"} 794
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 540
telemt_me_writer_restored_same_endpoint_total 515
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 736805
telemt_user_connections_current{user="hello"} 5666
telemt_user_octets_from_client{user="hello"} 9439797516 (8.79 GB)
telemt_user_octets_to_client{user="hello"} 133894176608 (124.70 GB)
telemt_user_unique_ips_current{user="hello"} 1712
telemt_user_unique_ips_recent_window{user="hello"} 818
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 5252.2 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83933
telemt_connections_bad_total 13577
telemt_connections_current 643
telemt_connections_me_current 643
telemt_handshake_timeouts_total 923
telemt_upstream_connect_attempt_total 951
telemt_upstream_connect_success_total 943
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 656
telemt_me_reconnect_success_total 651
telemt_me_reader_eof_total 662
telemt_me_idle_close_by_peer_total 662
telemt_me_route_drop_no_conn_total 44003
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80892
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 260
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 656
telemt_me_writer_restored_same_endpoint_total 643
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 65696
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 770076172 (734.40 MB)
telemt_user_octets_to_client{user="hello"} 26186161068 (24.39 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 67698.3 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3062370
telemt_connections_bad_total 200092
telemt_connections_current 4982
telemt_connections_me_current 4982
telemt_handshake_timeouts_total 55665
telemt_upstream_connect_attempt_total 11910
telemt_upstream_connect_success_total 11835
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 11910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8513
telemt_me_reconnect_success_total 8457
telemt_me_reader_eof_total 8943
telemt_me_idle_close_by_peer_total 8943
telemt_me_route_drop_no_conn_total 1040172
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2570558
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12700
telemt_desync_full_logged_total 4128
telemt_desync_suppressed_total 8572
telemt_desync_frames_bucket_total{bucket="1_2"} 2531
telemt_desync_frames_bucket_total{bucket="3_10"} 4511
telemt_desync_frames_bucket_total{bucket="gt_10"} 5658
telemt_pool_swap_total 70
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 8577
telemt_me_writer_restored_same_endpoint_total 8440
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 2568666
telemt_user_connections_current{user="hello"} 4982
telemt_user_octets_from_client{user="hello"} 54802943104 (51.04 GB)
telemt_user_octets_to_client{user="hello"} 1343407432400 (1.22 TB)
telemt_user_unique_ips_current{user="hello"} 1561
telemt_user_unique_ips_recent_window{user="hello"} 613
```