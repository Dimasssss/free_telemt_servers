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

# Server Metrics 2026-03-20 09:50:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 59593.3 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1418463
telemt_connections_bad_total 74142
telemt_connections_current 2054
telemt_connections_me_current 2054
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 37124
telemt_upstream_connect_attempt_total 11386
telemt_upstream_connect_success_total 11267
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 11386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 7234
telemt_me_reconnect_success_total 7179
telemt_me_reader_eof_total 7601
telemt_me_idle_close_by_peer_total 7599
telemt_me_route_drop_no_conn_total 424776
telemt_me_route_drop_channel_closed_total 264
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1163762
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6239
telemt_desync_full_logged_total 2189
telemt_desync_suppressed_total 4050
telemt_desync_frames_bucket_total{bucket="1_2"} 1357
telemt_desync_frames_bucket_total{bucket="3_10"} 2398
telemt_desync_frames_bucket_total{bucket="gt_10"} 2484
telemt_pool_swap_total 62
telemt_me_writer_close_signal_drop_total 144
telemt_me_writer_removed_unexpected_total 7257
telemt_me_writer_restored_same_endpoint_total 7166
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1163457
telemt_user_connections_current{user="hello"} 2054
telemt_user_octets_from_client{user="hello"} 41245323456 (38.41 GB)
telemt_user_octets_to_client{user="hello"} 393053828161 (366.06 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 671
telemt_user_unique_ips_recent_window{user="hello"} 291
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 76048.9 (21h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5800636
telemt_connections_bad_total 515050
telemt_connections_current 4033
telemt_connections_me_current 4033
telemt_handshake_timeouts_total 119104
telemt_upstream_connect_attempt_total 14039
telemt_upstream_connect_success_total 13741
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 14039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 14235
telemt_me_reconnect_success_total 8733
telemt_me_reader_eof_total 9360
telemt_me_idle_close_by_peer_total 9359
telemt_me_route_drop_no_conn_total 3594387
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4770599
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17542
telemt_desync_full_logged_total 5897
telemt_desync_suppressed_total 11645
telemt_desync_frames_bucket_total{bucket="1_2"} 3497
telemt_desync_frames_bucket_total{bucket="3_10"} 6874
telemt_desync_frames_bucket_total{bucket="gt_10"} 7171
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 3394
telemt_me_writer_close_signal_drop_total 132
telemt_me_writer_removed_unexpected_total 9029
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 8678
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 4772090
telemt_user_connections_current{user="hello"} 4033
telemt_user_octets_from_client{user="hello"} 64587231030 (60.15 GB)
telemt_user_octets_to_client{user="hello"} 1575884048142 (1.43 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1444
telemt_user_unique_ips_recent_window{user="hello"} 580
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 9390.8 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 617038
telemt_connections_bad_total 57786
telemt_connections_current 3371
telemt_connections_me_current 3371
telemt_handshake_timeouts_total 6781
telemt_upstream_connect_attempt_total 1751
telemt_upstream_connect_success_total 1751
telemt_upstream_connect_attempts_per_request{bucket="1"} 1751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 1201
telemt_me_reconnect_success_total 1188
telemt_me_reader_eof_total 1205
telemt_me_idle_close_by_peer_total 1205
telemt_me_route_drop_no_conn_total 223469
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498718
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2044
telemt_desync_full_logged_total 672
telemt_desync_suppressed_total 1372
telemt_desync_frames_bucket_total{bucket="1_2"} 397
telemt_desync_frames_bucket_total{bucket="3_10"} 713
telemt_desync_frames_bucket_total{bucket="gt_10"} 934
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 1183
telemt_me_writer_restored_same_endpoint_total 1188
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 498955
telemt_user_connections_current{user="hello"} 3371
telemt_user_octets_from_client{user="hello"} 8002381988 (7.45 GB)
telemt_user_octets_to_client{user="hello"} 191697264091 (178.53 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1259
telemt_user_unique_ips_recent_window{user="hello"} 479
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 76027.3 (21h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5615336
telemt_connections_bad_total 641016
telemt_connections_current 4798
telemt_connections_me_current 4798
telemt_handshake_timeouts_total 82068
telemt_upstream_connect_attempt_total 19767
telemt_upstream_connect_success_total 14708
telemt_upstream_connect_fail_total 5059
telemt_upstream_connect_attempts_per_request{bucket="1"} 19767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 911
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5059
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 3102
telemt_me_reconnect_attempts_total 9157
telemt_me_reconnect_success_total 8164
telemt_me_reader_eof_total 8570
telemt_me_idle_close_by_peer_total 8565
telemt_me_route_drop_no_conn_total 3733647
telemt_me_route_drop_channel_closed_total 403
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4076148
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 180
telemt_me_endpoint_quarantine_total 3
telemt_me_kdf_drift_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13340
telemt_desync_full_logged_total 4268
telemt_desync_suppressed_total 9072
telemt_desync_frames_bucket_total{bucket="1_2"} 3097
telemt_desync_frames_bucket_total{bucket="3_10"} 5009
telemt_desync_frames_bucket_total{bucket="gt_10"} 5234
telemt_pool_swap_total 74
telemt_me_writer_close_signal_drop_total 438
telemt_me_writer_removed_unexpected_total 8293
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 8163
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 4155558
telemt_user_connections_current{user="hello"} 4798
telemt_user_octets_from_client{user="hello"} 59356993959 (55.28 GB)
telemt_user_octets_to_client{user="hello"} 1437201452676 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 5696
telemt_user_msgs_to_client{user="hello"} 6360
telemt_user_unique_ips_current{user="hello"} 1580
telemt_user_unique_ips_recent_window{user="hello"} 658
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 76014.9 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7886997
telemt_connections_bad_total 346620
telemt_connections_current 5725
telemt_connections_me_current 5725
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 101672
telemt_upstream_connect_attempt_total 83567
telemt_upstream_connect_success_total 71775
telemt_upstream_connect_fail_total 11792
telemt_upstream_connect_attempts_per_request{bucket="1"} 83567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11792
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 222
telemt_me_reconnect_attempts_total 11783
telemt_me_reconnect_success_total 8621
telemt_me_reader_eof_total 8998
telemt_me_idle_close_by_peer_total 8996
telemt_me_route_drop_no_conn_total 12599252
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6845981
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
telemt_desync_total 15911
telemt_desync_full_logged_total 4640
telemt_desync_suppressed_total 11271
telemt_desync_frames_bucket_total{bucket="1_2"} 3522
telemt_desync_frames_bucket_total{bucket="3_10"} 6381
telemt_desync_frames_bucket_total{bucket="gt_10"} 6008
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 853
telemt_me_writer_removed_unexpected_total 9485
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8617
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 864
telemt_user_connections_total{user="hello"} 6905383
telemt_user_connections_current{user="hello"} 5725
telemt_user_octets_from_client{user="hello"} 57331855543 (53.39 GB)
telemt_user_octets_to_client{user="hello"} 955840374849 (890.20 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1718
telemt_user_unique_ips_recent_window{user="hello"} 1019
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 13597.8 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3026497
telemt_connections_bad_total 244025
telemt_connections_current 6375
telemt_connections_me_current 6375
telemt_handshake_timeouts_total 35046
telemt_upstream_connect_attempt_total 2244
telemt_upstream_connect_success_total 2231
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 1511
telemt_me_reconnect_success_total 1502
telemt_me_reader_eof_total 1550
telemt_me_idle_close_by_peer_total 1549
telemt_me_route_drop_no_conn_total 4618299
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2556989
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5526
telemt_desync_full_logged_total 1593
telemt_desync_suppressed_total 3933
telemt_desync_frames_bucket_total{bucket="1_2"} 1019
telemt_desync_frames_bucket_total{bucket="3_10"} 2261
telemt_desync_frames_bucket_total{bucket="gt_10"} 2246
telemt_pool_swap_total 8
telemt_me_writer_close_signal_drop_total 46
telemt_me_writer_removed_unexpected_total 1518
telemt_me_writer_restored_same_endpoint_total 1472
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 2551755
telemt_user_connections_current{user="hello"} 6375
telemt_user_octets_from_client{user="hello"} 22423862924 (20.88 GB)
telemt_user_octets_to_client{user="hello"} 323289337216 (301.09 GB)
telemt_user_unique_ips_current{user="hello"} 1987
telemt_user_unique_ips_recent_window{user="hello"} 873
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 3175.4 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73491
telemt_connections_bad_total 16406
telemt_connections_current 863
telemt_connections_me_current 863
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 1418
telemt_upstream_connect_attempt_total 2117
telemt_upstream_connect_success_total 2099
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 532
telemt_me_reconnect_success_total 528
telemt_me_reader_eof_total 489
telemt_me_idle_close_by_peer_total 489
telemt_me_route_drop_no_conn_total 22156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51614
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 127
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 21
telemt_me_writer_removed_unexpected_total 495
telemt_me_writer_restored_same_endpoint_total 526
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 53131
telemt_user_connections_current{user="hello"} 863
telemt_user_octets_from_client{user="hello"} 869152743 (828.89 MB)
telemt_user_octets_to_client{user="hello"} 9322054612 (8.68 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 75979.3 (21h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4052913
telemt_connections_bad_total 252739
telemt_connections_current 6407
telemt_connections_me_current 6407
telemt_handshake_timeouts_total 91450
telemt_upstream_connect_attempt_total 13272
telemt_upstream_connect_success_total 13188
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 13272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9470
telemt_me_reconnect_success_total 9402
telemt_me_reader_eof_total 9949
telemt_me_idle_close_by_peer_total 9948
telemt_me_route_drop_no_conn_total 1454993
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3422348
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16334
telemt_desync_full_logged_total 5426
telemt_desync_suppressed_total 10908
telemt_desync_frames_bucket_total{bucket="1_2"} 3410
telemt_desync_frames_bucket_total{bucket="3_10"} 5869
telemt_desync_frames_bucket_total{bucket="gt_10"} 7055
telemt_pool_swap_total 76
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 9546
telemt_me_writer_restored_same_endpoint_total 9385
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 3420250
telemt_user_connections_current{user="hello"} 6407
telemt_user_octets_from_client{user="hello"} 73715859724 (68.65 GB)
telemt_user_octets_to_client{user="hello"} 1720775830816 (1.57 TB)
telemt_user_unique_ips_current{user="hello"} 2048
telemt_user_unique_ips_recent_window{user="hello"} 820
```