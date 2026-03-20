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

# Server Metrics 2026-03-20 08:08:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 53461.8 (14h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1158399
telemt_connections_bad_total 64925
telemt_connections_current 1873
telemt_connections_me_current 1873
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30566
telemt_upstream_connect_attempt_total 10279
telemt_upstream_connect_success_total 10168
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 10279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6442
telemt_me_reconnect_success_total 6392
telemt_me_reader_eof_total 6767
telemt_me_idle_close_by_peer_total 6765
telemt_me_route_drop_no_conn_total 336787
telemt_me_route_drop_channel_closed_total 164
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 955277
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4821
telemt_desync_full_logged_total 1741
telemt_desync_suppressed_total 3080
telemt_desync_frames_bucket_total{bucket="1_2"} 980
telemt_desync_frames_bucket_total{bucket="3_10"} 1862
telemt_desync_frames_bucket_total{bucket="gt_10"} 1979
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 83
telemt_me_writer_removed_unexpected_total 6461
telemt_me_writer_restored_same_endpoint_total 6379
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 954802
telemt_user_connections_current{user="hello"} 1873
telemt_user_octets_from_client{user="hello"} 37694349412 (35.11 GB)
telemt_user_octets_to_client{user="hello"} 326760028921 (304.32 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 641
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 69917.4 (19h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5165336
telemt_connections_bad_total 458834
telemt_connections_current 3705
telemt_connections_me_current 3705
telemt_handshake_timeouts_total 109144
telemt_upstream_connect_attempt_total 12940
telemt_upstream_connect_success_total 12672
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 12940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12255
telemt_me_reconnect_success_total 7977
telemt_me_reader_eof_total 8534
telemt_me_idle_close_by_peer_total 8533
telemt_me_route_drop_no_conn_total 3134613
telemt_me_route_drop_channel_closed_total 55
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4263959
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15832
telemt_desync_full_logged_total 5233
telemt_desync_suppressed_total 10599
telemt_desync_frames_bucket_total{bucket="1_2"} 3132
telemt_desync_frames_bucket_total{bucket="3_10"} 6180
telemt_desync_frames_bucket_total{bucket="gt_10"} 6520
telemt_pool_swap_total 62
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 111
telemt_me_writer_removed_unexpected_total 8222
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7922
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 4266094
telemt_user_connections_current{user="hello"} 3705
telemt_user_octets_from_client{user="hello"} 56767225610 (52.87 GB)
telemt_user_octets_to_client{user="hello"} 1420998352006 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1314
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 3259.3 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155909
telemt_connections_bad_total 14763
telemt_connections_current 2603
telemt_connections_me_current 2603
telemt_handshake_timeouts_total 1558
telemt_upstream_connect_attempt_total 662
telemt_upstream_connect_success_total 662
telemt_upstream_connect_attempts_per_request{bucket="1"} 662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 418
telemt_me_reconnect_success_total 410
telemt_me_reader_eof_total 387
telemt_me_idle_close_by_peer_total 387
telemt_me_route_drop_no_conn_total 52981
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130151
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 557
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 357
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 269
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 392
telemt_me_writer_restored_same_endpoint_total 410
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 130370
telemt_user_connections_current{user="hello"} 2603
telemt_user_octets_from_client{user="hello"} 2404952528 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 49437251687 (46.04 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 955
telemt_user_unique_ips_recent_window{user="hello"} 370
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 69895.5 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4541796
telemt_connections_bad_total 560191
telemt_connections_current 4987
telemt_connections_me_current 4987
telemt_handshake_timeouts_total 68350
telemt_upstream_connect_attempt_total 12703
telemt_upstream_connect_success_total 12597
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 12703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5804
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3086
telemt_me_reconnect_attempts_total 8626
telemt_me_reconnect_success_total 7661
telemt_me_reader_eof_total 8023
telemt_me_idle_close_by_peer_total 8018
telemt_me_route_drop_no_conn_total 2875956
telemt_me_route_drop_channel_closed_total 280
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3276774
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11521
telemt_desync_full_logged_total 3642
telemt_desync_suppressed_total 7879
telemt_desync_frames_bucket_total{bucket="1_2"} 2738
telemt_desync_frames_bucket_total{bucket="3_10"} 4376
telemt_desync_frames_bucket_total{bucket="gt_10"} 4407
telemt_pool_swap_total 69
telemt_me_writer_close_signal_drop_total 334
telemt_me_writer_removed_unexpected_total 7763
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7660
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 3283109
telemt_user_connections_current{user="hello"} 4987
telemt_user_octets_from_client{user="hello"} 47856427866 (44.57 GB)
telemt_user_octets_to_client{user="hello"} 1225097028372 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1595
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 69883.5 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5649516
telemt_connections_bad_total 305066
telemt_connections_current 5372
telemt_connections_me_current 5372
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 77167
telemt_upstream_connect_attempt_total 82604
telemt_upstream_connect_success_total 70869
telemt_upstream_connect_fail_total 11735
telemt_upstream_connect_attempts_per_request{bucket="1"} 82604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11735
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 11151
telemt_me_reconnect_success_total 8030
telemt_me_reader_eof_total 8358
telemt_me_idle_close_by_peer_total 8356
telemt_me_route_drop_no_conn_total 7506295
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4799758
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
telemt_desync_total 13820
telemt_desync_full_logged_total 3982
telemt_desync_suppressed_total 9838
telemt_desync_frames_bucket_total{bucket="1_2"} 3106
telemt_desync_frames_bucket_total{bucket="3_10"} 5508
telemt_desync_frames_bucket_total{bucket="gt_10"} 5206
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 828
telemt_me_writer_removed_unexpected_total 8858
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8026
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 828
telemt_user_connections_total{user="hello"} 4858986
telemt_user_connections_current{user="hello"} 5372
telemt_user_octets_from_client{user="hello"} 49667020519 (46.26 GB)
telemt_user_octets_to_client{user="hello"} 884757857017 (823.99 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1533
telemt_user_unique_ips_recent_window{user="hello"} 871
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 7466.6 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1526952
telemt_connections_bad_total 113913
telemt_connections_current 6308
telemt_connections_me_current 6308
telemt_handshake_timeouts_total 20367
telemt_upstream_connect_attempt_total 1282
telemt_upstream_connect_success_total 1274
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 850
telemt_me_reconnect_success_total 847
telemt_me_reader_eof_total 847
telemt_me_idle_close_by_peer_total 847
telemt_me_route_drop_no_conn_total 2345275
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1301729
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2814
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1982
telemt_desync_frames_bucket_total{bucket="1_2"} 537
telemt_desync_frames_bucket_total{bucket="3_10"} 1133
telemt_desync_frames_bucket_total{bucket="gt_10"} 1144
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 848
telemt_me_writer_restored_same_endpoint_total 817
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1301518
telemt_user_connections_current{user="hello"} 6308
telemt_user_octets_from_client{user="hello"} 12675029372 (11.80 GB)
telemt_user_octets_to_client{user="hello"} 181935139092 (169.44 GB)
telemt_user_unique_ips_current{user="hello"} 1843
telemt_user_unique_ips_recent_window{user="hello"} 1083
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 7401.9 (2h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116913
telemt_connections_bad_total 15006
telemt_connections_current 679
telemt_connections_me_current 679
telemt_handshake_timeouts_total 1440
telemt_upstream_connect_attempt_total 1342
telemt_upstream_connect_success_total 1330
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 913
telemt_me_reconnect_success_total 907
telemt_me_reader_eof_total 934
telemt_me_idle_close_by_peer_total 934
telemt_me_route_drop_no_conn_total 61105
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111070
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 346
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 228
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 916
telemt_me_writer_restored_same_endpoint_total 899
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 94018
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 1365648272 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 37507472976 (34.93 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 69848.0 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3294455
telemt_connections_bad_total 216618
telemt_connections_current 5489
telemt_connections_me_current 5489
telemt_handshake_timeouts_total 61094
telemt_upstream_connect_attempt_total 12236
telemt_upstream_connect_success_total 12160
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8751
telemt_me_reconnect_success_total 8693
telemt_me_reader_eof_total 9187
telemt_me_idle_close_by_peer_total 9187
telemt_me_route_drop_no_conn_total 1126752
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2766413
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13544
telemt_desync_full_logged_total 4454
telemt_desync_suppressed_total 9090
telemt_desync_frames_bucket_total{bucket="1_2"} 2695
telemt_desync_frames_bucket_total{bucket="3_10"} 4855
telemt_desync_frames_bucket_total{bucket="gt_10"} 5994
telemt_pool_swap_total 71
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 8818
telemt_me_writer_restored_same_endpoint_total 8676
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 2764357
telemt_user_connections_current{user="hello"} 5489
telemt_user_octets_from_client{user="hello"} 58810740988 (54.77 GB)
telemt_user_octets_to_client{user="hello"} 1435821888272 (1.31 TB)
telemt_user_unique_ips_current{user="hello"} 1746
telemt_user_unique_ips_recent_window{user="hello"} 713
```