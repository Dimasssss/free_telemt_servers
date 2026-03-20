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

# Server Metrics 2026-03-20 08:03:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 53142.8 (14h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1145995
telemt_connections_bad_total 64814
telemt_connections_current 2032
telemt_connections_me_current 2032
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30005
telemt_upstream_connect_attempt_total 10183
telemt_upstream_connect_success_total 10072
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 10183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6379
telemt_me_reconnect_success_total 6331
telemt_me_reader_eof_total 6702
telemt_me_idle_close_by_peer_total 6701
telemt_me_route_drop_no_conn_total 332335
telemt_me_route_drop_channel_closed_total 159
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 944431
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4776
telemt_desync_full_logged_total 1721
telemt_desync_suppressed_total 3055
telemt_desync_frames_bucket_total{bucket="1_2"} 969
telemt_desync_frames_bucket_total{bucket="3_10"} 1848
telemt_desync_frames_bucket_total{bucket="gt_10"} 1959
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 78
telemt_me_writer_removed_unexpected_total 6401
telemt_me_writer_restored_same_endpoint_total 6318
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 943933
telemt_user_connections_current{user="hello"} 2032
telemt_user_octets_from_client{user="hello"} 37541925140 (34.96 GB)
telemt_user_octets_to_client{user="hello"} 323332016909 (301.13 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 69598.5 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5135358
telemt_connections_bad_total 454582
telemt_connections_current 4050
telemt_connections_me_current 4050
telemt_handshake_timeouts_total 108698
telemt_upstream_connect_attempt_total 12914
telemt_upstream_connect_success_total 12646
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 12914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12229
telemt_me_reconnect_success_total 7951
telemt_me_reader_eof_total 8508
telemt_me_idle_close_by_peer_total 8507
telemt_me_route_drop_no_conn_total 3124794
telemt_me_route_drop_channel_closed_total 55
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4240956
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15722
telemt_desync_full_logged_total 5191
telemt_desync_suppressed_total 10531
telemt_desync_frames_bucket_total{bucket="1_2"} 3100
telemt_desync_frames_bucket_total{bucket="3_10"} 6140
telemt_desync_frames_bucket_total{bucket="gt_10"} 6482
telemt_pool_swap_total 62
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 111
telemt_me_writer_removed_unexpected_total 8196
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7896
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 4243071
telemt_user_connections_current{user="hello"} 4050
telemt_user_octets_from_client{user="hello"} 56553169522 (52.67 GB)
telemt_user_octets_to_client{user="hello"} 1412732808354 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1372
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 2940.6 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134474
telemt_connections_bad_total 13697
telemt_connections_current 2649
telemt_connections_me_current 2649
telemt_handshake_timeouts_total 1369
telemt_upstream_connect_attempt_total 629
telemt_upstream_connect_success_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 385
telemt_me_reconnect_success_total 378
telemt_me_reader_eof_total 353
telemt_me_idle_close_by_peer_total 353
telemt_me_route_drop_no_conn_total 45745
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112480
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 478
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 313
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 161
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 358
telemt_me_writer_restored_same_endpoint_total 378
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 112659
telemt_user_connections_current{user="hello"} 2649
telemt_user_octets_from_client{user="hello"} 2217873948 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 42926377479 (39.98 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 960
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 69579.4 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5555682
telemt_connections_bad_total 302051
telemt_connections_current 5276
telemt_connections_me_current 5276
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 76174
telemt_upstream_connect_attempt_total 82573
telemt_upstream_connect_success_total 70838
telemt_upstream_connect_fail_total 11735
telemt_upstream_connect_attempts_per_request{bucket="1"} 82573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11735
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 11120
telemt_me_reconnect_success_total 7999
telemt_me_reader_eof_total 8327
telemt_me_idle_close_by_peer_total 8325
telemt_me_route_drop_no_conn_total 7324182
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4714857
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
telemt_desync_total 13728
telemt_desync_full_logged_total 3955
telemt_desync_suppressed_total 9773
telemt_desync_frames_bucket_total{bucket="1_2"} 3079
telemt_desync_frames_bucket_total{bucket="3_10"} 5472
telemt_desync_frames_bucket_total{bucket="gt_10"} 5177
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 827
telemt_me_writer_removed_unexpected_total 8827
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7995
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 828
telemt_user_connections_total{user="hello"} 4774088
telemt_user_connections_current{user="hello"} 5276
telemt_user_octets_from_client{user="hello"} 49317971219 (45.93 GB)
telemt_user_octets_to_client{user="hello"} 881300677693 (820.78 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1514
telemt_user_unique_ips_recent_window{user="hello"} 820
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 7147.5 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1408973
telemt_connections_bad_total 106801
telemt_connections_current 6201
telemt_connections_me_current 6201
telemt_handshake_timeouts_total 19166
telemt_upstream_connect_attempt_total 1156
telemt_upstream_connect_success_total 1150
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 773
telemt_me_reconnect_success_total 770
telemt_me_reader_eof_total 770
telemt_me_idle_close_by_peer_total 770
telemt_me_route_drop_no_conn_total 2094117
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1198890
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2638
telemt_desync_full_logged_total 786
telemt_desync_suppressed_total 1852
telemt_desync_frames_bucket_total{bucket="1_2"} 501
telemt_desync_frames_bucket_total{bucket="3_10"} 1067
telemt_desync_frames_bucket_total{bucket="gt_10"} 1070
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 771
telemt_me_writer_restored_same_endpoint_total 740
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1198692
telemt_user_connections_current{user="hello"} 6201
telemt_user_octets_from_client{user="hello"} 12205253628 (11.37 GB)
telemt_user_octets_to_client{user="hello"} 175243426920 (163.21 GB)
telemt_user_unique_ips_current{user="hello"} 1794
telemt_user_unique_ips_recent_window{user="hello"} 1045
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 7083.2 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110709
telemt_connections_bad_total 14646
telemt_connections_current 741
telemt_connections_me_current 741
telemt_handshake_timeouts_total 1343
telemt_upstream_connect_attempt_total 1255
telemt_upstream_connect_success_total 1245
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 872
telemt_me_reconnect_success_total 867
telemt_me_reader_eof_total 892
telemt_me_idle_close_by_peer_total 892
telemt_me_route_drop_no_conn_total 57748
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106608
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 330
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 874
telemt_me_writer_restored_same_endpoint_total 859
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 89536
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 1336228824 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 35871555996 (33.41 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 69529.2 (19h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3257505
telemt_connections_bad_total 215633
telemt_connections_current 5781
telemt_connections_me_current 5781
telemt_handshake_timeouts_total 59564
telemt_upstream_connect_attempt_total 12185
telemt_upstream_connect_success_total 12109
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8700
telemt_me_reconnect_success_total 8642
telemt_me_reader_eof_total 9136
telemt_me_idle_close_by_peer_total 9136
telemt_me_route_drop_no_conn_total 1113585
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2735172
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13411
telemt_desync_full_logged_total 4401
telemt_desync_suppressed_total 9010
telemt_desync_frames_bucket_total{bucket="1_2"} 2669
telemt_desync_frames_bucket_total{bucket="3_10"} 4806
telemt_desync_frames_bucket_total{bucket="gt_10"} 5936
telemt_pool_swap_total 71
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 8767
telemt_me_writer_restored_same_endpoint_total 8625
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 2733115
telemt_user_connections_current{user="hello"} 5781
telemt_user_octets_from_client{user="hello"} 58337783812 (54.33 GB)
telemt_user_octets_to_client{user="hello"} 1421371074276 (1.29 TB)
telemt_user_unique_ips_current{user="hello"} 1738
telemt_user_unique_ips_recent_window{user="hello"} 746
```