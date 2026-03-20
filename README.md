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

# Server Metrics 2026-03-20 07:27:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 51006.4 (14h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1070749
telemt_connections_bad_total 63435
telemt_connections_current 1693
telemt_connections_me_current 1693
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 27473
telemt_upstream_connect_attempt_total 9874
telemt_upstream_connect_success_total 9765
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 9874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6170
telemt_me_reconnect_success_total 6124
telemt_me_reader_eof_total 6484
telemt_me_idle_close_by_peer_total 6483
telemt_me_route_drop_no_conn_total 309855
telemt_me_route_drop_channel_closed_total 141
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879047
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4476
telemt_desync_full_logged_total 1613
telemt_desync_suppressed_total 2863
telemt_desync_frames_bucket_total{bucket="1_2"} 901
telemt_desync_frames_bucket_total{bucket="3_10"} 1733
telemt_desync_frames_bucket_total{bucket="gt_10"} 1842
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 6192
telemt_me_writer_restored_same_endpoint_total 6111
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 878463
telemt_user_connections_current{user="hello"} 1693
telemt_user_octets_from_client{user="hello"} 35411609928 (32.98 GB)
telemt_user_octets_to_client{user="hello"} 302785364025 (281.99 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 67462.0 (18h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4963151
telemt_connections_bad_total 441432
telemt_connections_current 4224
telemt_connections_me_current 4224
telemt_handshake_timeouts_total 103361
telemt_upstream_connect_attempt_total 12533
telemt_upstream_connect_success_total 12276
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 12533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 11988
telemt_me_reconnect_success_total 7716
telemt_me_reader_eof_total 8254
telemt_me_idle_close_by_peer_total 8253
telemt_me_route_drop_no_conn_total 3070225
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4099371
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15230
telemt_desync_full_logged_total 5009
telemt_desync_suppressed_total 10221
telemt_desync_frames_bucket_total{bucket="1_2"} 3006
telemt_desync_frames_bucket_total{bucket="3_10"} 5944
telemt_desync_frames_bucket_total{bucket="gt_10"} 6280
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 107
telemt_me_writer_removed_unexpected_total 7957
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7661
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 4101132
telemt_user_connections_current{user="hello"} 4224
telemt_user_octets_from_client{user="hello"} 54655815910 (50.90 GB)
telemt_user_octets_to_client{user="hello"} 1361138429546 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1484
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 803.5 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15122
telemt_connections_bad_total 1073
telemt_connections_current 1242
telemt_connections_me_current 1242
telemt_handshake_timeouts_total 112
telemt_upstream_connect_attempt_total 252
telemt_upstream_connect_success_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 85
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 138
telemt_me_reconnect_success_total 135
telemt_me_reader_eof_total 94
telemt_me_idle_close_by_peer_total 94
telemt_me_route_drop_no_conn_total 4651
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13186
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 99
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_me_writer_close_signal_drop_total 21
telemt_me_writer_removed_unexpected_total 115
telemt_me_writer_restored_same_endpoint_total 135
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 13240
telemt_user_connections_current{user="hello"} 1242
telemt_user_octets_from_client{user="hello"} 151403888 (144.39 MB)
telemt_user_octets_to_client{user="hello"} 4162619663 (3.88 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 67440.3 (18h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4249939
telemt_connections_bad_total 542765
telemt_connections_current 4112
telemt_connections_me_current 4112
telemt_handshake_timeouts_total 65113
telemt_upstream_connect_attempt_total 12351
telemt_upstream_connect_success_total 12245
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 12351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3086
telemt_me_reconnect_attempts_total 8406
telemt_me_reconnect_success_total 7442
telemt_me_reader_eof_total 7787
telemt_me_idle_close_by_peer_total 7782
telemt_me_route_drop_no_conn_total 2785674
telemt_me_route_drop_channel_closed_total 262
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3055647
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10785
telemt_desync_full_logged_total 3385
telemt_desync_suppressed_total 7400
telemt_desync_frames_bucket_total{bucket="1_2"} 2575
telemt_desync_frames_bucket_total{bucket="3_10"} 4122
telemt_desync_frames_bucket_total{bucket="gt_10"} 4088
telemt_pool_swap_total 66
telemt_me_writer_close_signal_drop_total 318
telemt_me_writer_removed_unexpected_total 7540
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7441
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 3062020
telemt_user_connections_current{user="hello"} 4112
telemt_user_octets_from_client{user="hello"} 42680298882 (39.75 GB)
telemt_user_octets_to_client{user="hello"} 1145794381024 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1372
telemt_user_unique_ips_recent_window{user="hello"} 538
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 67427.9 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4821965
telemt_connections_bad_total 291818
telemt_connections_current 5067
telemt_connections_me_current 5067
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 67619
telemt_upstream_connect_attempt_total 68182
telemt_upstream_connect_success_total 63441
telemt_upstream_connect_fail_total 4741
telemt_upstream_connect_attempts_per_request{bucket="1"} 68182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4741
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 10694
telemt_me_reconnect_success_total 7706
telemt_me_reader_eof_total 8049
telemt_me_idle_close_by_peer_total 8048
telemt_me_route_drop_no_conn_total 5940385
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4062281
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13169
telemt_desync_full_logged_total 3815
telemt_desync_suppressed_total 9354
telemt_desync_frames_bucket_total{bucket="1_2"} 2943
telemt_desync_frames_bucket_total{bucket="3_10"} 5219
telemt_desync_frames_bucket_total{bucket="gt_10"} 5007
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 681
telemt_me_writer_removed_unexpected_total 8437
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7702
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 731
telemt_user_connections_total{user="hello"} 4113714
telemt_user_connections_current{user="hello"} 5067
telemt_user_octets_from_client{user="hello"} 47063181264 (43.83 GB)
telemt_user_octets_to_client{user="hello"} 858390575187 (799.44 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1501
telemt_user_unique_ips_recent_window{user="hello"} 817
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 5010.9 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814597
telemt_connections_bad_total 72139
telemt_connections_current 5345
telemt_connections_me_current 5345
telemt_handshake_timeouts_total 14710
telemt_upstream_connect_attempt_total 803
telemt_upstream_connect_success_total 799
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 510
telemt_me_reconnect_success_total 508
telemt_me_reader_eof_total 493
telemt_me_idle_close_by_peer_total 493
telemt_me_route_drop_no_conn_total 1020720
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678852
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1888
telemt_desync_full_logged_total 585
telemt_desync_suppressed_total 1303
telemt_desync_frames_bucket_total{bucket="1_2"} 380
telemt_desync_frames_bucket_total{bucket="3_10"} 771
telemt_desync_frames_bucket_total{bucket="gt_10"} 737
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 503
telemt_me_writer_restored_same_endpoint_total 478
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 678825
telemt_user_connections_current{user="hello"} 5345
telemt_user_octets_from_client{user="hello"} 9002676648 (8.38 GB)
telemt_user_octets_to_client{user="hello"} 126438014240 (117.75 GB)
telemt_user_unique_ips_current{user="hello"} 1666
telemt_user_unique_ips_recent_window{user="hello"} 779
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 4945.9 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79878
telemt_connections_bad_total 13323
telemt_connections_current 728
telemt_connections_me_current 728
telemt_handshake_timeouts_total 885
telemt_upstream_connect_attempt_total 931
telemt_upstream_connect_success_total 923
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 636
telemt_me_reconnect_success_total 631
telemt_me_reader_eof_total 641
telemt_me_idle_close_by_peer_total 641
telemt_me_route_drop_no_conn_total 42479
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77369
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 251
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 168
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 635
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 62197
telemt_user_connections_current{user="hello"} 728
telemt_user_octets_from_client{user="hello"} 731898676 (697.99 MB)
telemt_user_octets_to_client{user="hello"} 24624676052 (22.93 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 67392.4 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3030223
telemt_connections_bad_total 195723
telemt_connections_current 4751
telemt_connections_me_current 4751
telemt_handshake_timeouts_total 55484
telemt_upstream_connect_attempt_total 11826
telemt_upstream_connect_success_total 11752
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 11826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8474
telemt_me_reconnect_success_total 8418
telemt_me_reader_eof_total 8898
telemt_me_idle_close_by_peer_total 8898
telemt_me_route_drop_no_conn_total 1031076
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2544696
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12637
telemt_desync_full_logged_total 4105
telemt_desync_suppressed_total 8532
telemt_desync_frames_bucket_total{bucket="1_2"} 2521
telemt_desync_frames_bucket_total{bucket="3_10"} 4477
telemt_desync_frames_bucket_total{bucket="gt_10"} 5639
telemt_pool_swap_total 69
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 8536
telemt_me_writer_restored_same_endpoint_total 8401
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 2542786
telemt_user_connections_current{user="hello"} 4751
telemt_user_octets_from_client{user="hello"} 54381309184 (50.65 GB)
telemt_user_octets_to_client{user="hello"} 1329862407784 (1.21 TB)
telemt_user_unique_ips_current{user="hello"} 1546
telemt_user_unique_ips_recent_window{user="hello"} 635
```