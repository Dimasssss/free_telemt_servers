# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 03:57:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 24673.6 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382083
telemt_connections_bad_total 24554
telemt_connections_current 922
telemt_connections_me_current 922
telemt_handshake_timeouts_total 20922
telemt_upstream_connect_attempt_total 10369
telemt_upstream_connect_success_total 10368
telemt_upstream_connect_attempts_per_request{bucket="1"} 10368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 289
telemt_me_reconnect_success_total 163
telemt_me_reader_eof_total 159
telemt_me_idle_close_by_peer_total 159
telemt_me_route_drop_no_conn_total 74193
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316340
telemt_me_endpoint_quarantine_total 198
telemt_me_single_endpoint_shadow_rotate_total 208
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 2877
telemt_desync_full_logged_total 785
telemt_desync_suppressed_total 2092
telemt_desync_frames_bucket_total{bucket="1_2"} 987
telemt_desync_frames_bucket_total{bucket="3_10"} 1085
telemt_desync_frames_bucket_total{bucket="gt_10"} 805
telemt_pool_swap_total 27
telemt_pool_force_close_total 710
telemt_me_writer_close_signal_drop_total 50
telemt_me_draining_writers_reap_progress_total 9359
telemt_me_writer_removed_unexpected_total 157
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 627
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8881
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 705
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8649
telemt_me_writer_teardown_success_total{mode="normal"} 9508
telemt_me_writer_teardown_noop_total 9360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18868
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.730813
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18868
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 50
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 146
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 315613
telemt_user_connections_current{user="hello"} 922
telemt_user_octets_from_client{user="hello"} 4070067572 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 108630718872 (101.17 GB)
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 38040.0 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 849728
telemt_connections_bad_total 56309
telemt_connections_current 462
telemt_connections_me_current 462
telemt_handshake_timeouts_total 30696
telemt_upstream_connect_attempt_total 17843
telemt_upstream_connect_success_total 17565
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 17819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_reconnect_attempts_total 1498
telemt_me_reconnect_success_total 549
telemt_me_reader_eof_total 486
telemt_me_idle_close_by_peer_total 486
telemt_me_route_drop_no_conn_total 351609
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 672384
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 309
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 2857
telemt_desync_full_logged_total 1649
telemt_desync_suppressed_total 1208
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 1084
telemt_desync_frames_bucket_total{bucket="gt_10"} 1169
telemt_pool_swap_total 41
telemt_pool_force_close_total 1098
telemt_me_writer_close_signal_drop_total 78
telemt_me_draining_writers_reap_progress_total 15830
telemt_me_writer_removed_unexpected_total 462
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1319
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14984
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1076
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14732
telemt_me_writer_teardown_success_total{mode="normal"} 16303
telemt_me_writer_teardown_noop_total 15830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32133
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.866797
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32133
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 78
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 407
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 671355
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 10914935580 (10.17 GB)
telemt_user_octets_to_client{user="hello"} 240331210948 (223.83 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 112899.9 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7910913
telemt_connections_bad_total 656430
telemt_connections_current 2063
telemt_connections_me_current 2063
telemt_handshake_timeouts_total 260337
telemt_upstream_connect_attempt_total 42140
telemt_upstream_connect_success_total 42063
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 42070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1623
telemt_me_reconnect_success_total 842
telemt_me_reader_eof_total 851
telemt_me_idle_close_by_peer_total 851
telemt_me_route_drop_no_conn_total 4563847
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6390936
telemt_me_endpoint_quarantine_total 729
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 845
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 26812
telemt_desync_full_logged_total 8904
telemt_desync_suppressed_total 17908
telemt_desync_frames_bucket_total{bucket="1_2"} 5790
telemt_desync_frames_bucket_total{bucket="3_10"} 10480
telemt_desync_frames_bucket_total{bucket="gt_10"} 10542
telemt_pool_swap_total 122
telemt_pool_force_close_total 4018
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 38467
telemt_me_writer_removed_unexpected_total 819
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3203
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35618
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3778
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34449
telemt_me_writer_teardown_success_total{mode="normal"} 38821
telemt_me_writer_teardown_noop_total 38511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77332
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 162.423911
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77332
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 750
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6382811
telemt_user_connections_current{user="hello"} 2063
telemt_user_octets_from_client{user="hello"} 108753193408 (101.28 GB)
telemt_user_octets_to_client{user="hello"} 2140219538412 (1.95 TB)
telemt_user_unique_ips_current{user="hello"} 987
telemt_user_unique_ips_recent_window{user="hello"} 371
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 112901.1 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6544266
telemt_connections_bad_total 593019
telemt_connections_current 1995
telemt_connections_me_current 1995
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 217520
telemt_upstream_connect_attempt_total 46088
telemt_upstream_connect_success_total 45694
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 45891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1968
telemt_me_reconnect_success_total 899
telemt_me_reader_eof_total 871
telemt_me_idle_close_by_peer_total 871
telemt_me_route_drop_no_conn_total 2280473
telemt_me_route_drop_channel_closed_total 274
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4880858
telemt_me_endpoint_quarantine_total 713
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 871
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 22939
telemt_desync_full_logged_total 7823
telemt_desync_suppressed_total 15116
telemt_desync_frames_bucket_total{bucket="1_2"} 5512
telemt_desync_frames_bucket_total{bucket="3_10"} 8909
telemt_desync_frames_bucket_total{bucket="gt_10"} 8518
telemt_pool_swap_total 123
telemt_pool_force_close_total 3650
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 36919
telemt_me_writer_removed_unexpected_total 855
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3063
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34649
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3433
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 217
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33269
telemt_me_writer_teardown_success_total{mode="normal"} 37712
telemt_me_writer_teardown_noop_total 36925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74637
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.491458
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74637
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 786
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4802594
telemt_user_connections_current{user="hello"} 1995
telemt_user_octets_from_client{user="hello"} 142439253573 (132.66 GB)
telemt_user_octets_to_client{user="hello"} 2279814053983 (2.07 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 956
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 112866.4 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6414677
telemt_connections_bad_total 551159
telemt_connections_current 1533
telemt_connections_me_current 1533
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 209929
telemt_upstream_connect_attempt_total 52304
telemt_upstream_connect_success_total 51864
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 52004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2229
telemt_me_reconnect_success_total 985
telemt_me_reader_eof_total 927
telemt_me_idle_close_by_peer_total 927
telemt_me_route_drop_no_conn_total 2216167
telemt_me_route_drop_channel_closed_total 127
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4766011
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 843
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 84
telemt_desync_total 22824
telemt_desync_full_logged_total 7699
telemt_desync_suppressed_total 15125
telemt_desync_frames_bucket_total{bucket="1_2"} 5575
telemt_desync_frames_bucket_total{bucket="3_10"} 8746
telemt_desync_frames_bucket_total{bucket="gt_10"} 8503
telemt_pool_swap_total 121
telemt_pool_force_close_total 3507
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 399
telemt_me_draining_writers_reap_progress_total 37940
telemt_me_writer_removed_unexpected_total 909
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3197
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35668
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3292
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34433
telemt_me_writer_teardown_success_total{mode="normal"} 38865
telemt_me_writer_teardown_noop_total 37952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76817
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.179969
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76817
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 399
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 859
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4761194
telemt_user_connections_current{user="hello"} 1533
telemt_user_octets_from_client{user="hello"} 135133902223 (125.85 GB)
telemt_user_octets_to_client{user="hello"} 2182414518951 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 756
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 112904.3 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20666144
telemt_connections_bad_total 1696204
telemt_connections_current 2745
telemt_connections_me_current 2745
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 623056
telemt_upstream_connect_attempt_total 202967
telemt_upstream_connect_success_total 184680
telemt_upstream_connect_fail_total 16469
telemt_upstream_connect_attempts_per_request{bucket="1"} 201149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8949
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16469
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65145
telemt_me_reconnect_success_total 2412
telemt_me_reader_eof_total 1496
telemt_me_idle_close_by_peer_total 1495
telemt_me_route_drop_no_conn_total 39555896
telemt_me_route_drop_channel_closed_total 127
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16652348
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 882
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 887
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 32260
telemt_desync_full_logged_total 9707
telemt_desync_suppressed_total 22553
telemt_desync_frames_bucket_total{bucket="1_2"} 6997
telemt_desync_frames_bucket_total{bucket="3_10"} 14309
telemt_desync_frames_bucket_total{bucket="gt_10"} 10954
telemt_pool_swap_total 117
telemt_pool_force_close_total 3773
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 829
telemt_me_draining_writers_reap_progress_total 35443
telemt_me_writer_removed_unexpected_total 2237
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4791
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32632
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3244
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 529
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31670
telemt_me_writer_teardown_success_total{mode="normal"} 37423
telemt_me_writer_teardown_noop_total 35470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72893
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 216.553896
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72893
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 829
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1637
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 16787128
telemt_user_connections_current{user="hello"} 2745
telemt_user_octets_from_client{user="hello"} 233230010244 (217.21 GB)
telemt_user_octets_to_client{user="hello"} 1255433472547 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1240
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 112871.8 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6178988
telemt_connections_bad_total 599016
telemt_connections_current 1971
telemt_connections_me_current 1971
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 130232
telemt_upstream_connect_attempt_total 60964
telemt_upstream_connect_success_total 60268
telemt_upstream_connect_fail_total 594
telemt_upstream_connect_attempts_per_request{bucket="1"} 60862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 594
telemt_me_reconnect_attempts_total 69760
telemt_me_reconnect_success_total 1822
telemt_me_reader_eof_total 1605
telemt_me_idle_close_by_peer_total 1604
telemt_me_route_drop_no_conn_total 2410216
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4796169
telemt_me_endpoint_quarantine_total 768
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 859
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 23988
telemt_desync_full_logged_total 8411
telemt_desync_suppressed_total 15577
telemt_desync_frames_bucket_total{bucket="1_2"} 4664
telemt_desync_frames_bucket_total{bucket="3_10"} 9279
telemt_desync_frames_bucket_total{bucket="gt_10"} 10045
telemt_pool_swap_total 117
telemt_pool_force_close_total 3344
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 402
telemt_me_draining_writers_reap_progress_total 39984
telemt_me_writer_removed_unexpected_total 1642
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4065
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37593
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2943
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36640
telemt_me_writer_teardown_success_total{mode="normal"} 41658
telemt_me_writer_teardown_noop_total 39985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81643
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.266641
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81643
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 402
telemt_me_refill_failed_total 4210
telemt_me_writer_restored_same_endpoint_total 1530
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 4788813
telemt_user_connections_current{user="hello"} 1971
telemt_user_octets_from_client{user="hello"} 126200849092 (117.53 GB)
telemt_user_octets_to_client{user="hello"} 1965353126778 (1.79 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 893
telemt_user_unique_ips_recent_window{user="hello"} 405
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 49707.5 (13h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4116491
telemt_connections_bad_total 175037
telemt_connections_current 1306
telemt_connections_me_current 1306
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1657426
telemt_upstream_connect_attempt_total 29714
telemt_upstream_connect_success_total 29518
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 29707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 45964
telemt_me_reconnect_success_total 1001
telemt_me_reader_eof_total 687
telemt_me_idle_close_by_peer_total 687
telemt_me_route_drop_no_conn_total 1040587
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2012678
telemt_me_endpoint_quarantine_total 372
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 385
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10799
telemt_desync_full_logged_total 3742
telemt_desync_suppressed_total 7057
telemt_desync_frames_bucket_total{bucket="1_2"} 1981
telemt_desync_frames_bucket_total{bucket="3_10"} 4139
telemt_desync_frames_bucket_total{bucket="gt_10"} 4679
telemt_pool_swap_total 54
telemt_pool_force_close_total 1593
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 145
telemt_me_draining_writers_reap_progress_total 18558
telemt_me_writer_removed_unexpected_total 760
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1633
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17712
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16965
telemt_me_writer_teardown_success_total{mode="normal"} 19345
telemt_me_writer_teardown_noop_total 18560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37905
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.507751
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37905
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 145
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 894
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2016151
telemt_user_connections_current{user="hello"} 1306
telemt_user_octets_from_client{user="hello"} 55432497028 (51.63 GB)
telemt_user_octets_to_client{user="hello"} 857718429570 (798.81 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 630
telemt_user_unique_ips_recent_window{user="hello"} 573
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 30678.9 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217875
telemt_connections_bad_total 1808
telemt_connections_current 359
telemt_connections_me_current 359
telemt_handshake_timeouts_total 5887
telemt_upstream_connect_attempt_total 14862
telemt_upstream_connect_success_total 14826
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 14860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 337
telemt_me_reconnect_success_total 195
telemt_me_reader_eof_total 199
telemt_me_idle_close_by_peer_total 199
telemt_me_route_drop_no_conn_total 60233
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192623
telemt_me_endpoint_quarantine_total 292
telemt_me_single_endpoint_shadow_rotate_total 265
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 48
telemt_me_writers_warm_current 34
telemt_desync_total 1100
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 814
telemt_desync_frames_bucket_total{bucket="1_2"} 403
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 33
telemt_pool_force_close_total 737
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 13399
telemt_me_writer_removed_unexpected_total 192
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 845
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12753
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 735
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12662
telemt_me_writer_teardown_success_total{mode="normal"} 13598
telemt_me_writer_teardown_noop_total 13399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26997
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.074932
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26997
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 176
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 192291
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 3334914768 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 117465820684 (109.40 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 112876.3 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7497656
telemt_connections_bad_total 755008
telemt_connections_current 2132
telemt_connections_me_current 2132
telemt_handshake_timeouts_total 214034
telemt_upstream_connect_attempt_total 44508
telemt_upstream_connect_success_total 44346
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 44471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22349
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_reconnect_attempts_total 1639
telemt_me_reconnect_success_total 872
telemt_me_reader_eof_total 859
telemt_me_idle_close_by_peer_total 859
telemt_me_route_drop_no_conn_total 2149616
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5586593
telemt_me_endpoint_quarantine_total 806
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 869
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 21882
telemt_desync_full_logged_total 7185
telemt_desync_suppressed_total 14697
telemt_desync_frames_bucket_total{bucket="1_2"} 5496
telemt_desync_frames_bucket_total{bucket="3_10"} 7926
telemt_desync_frames_bucket_total{bucket="gt_10"} 8460
telemt_pool_swap_total 125
telemt_pool_force_close_total 3335
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 40173
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3133
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37889
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3247
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36838
telemt_me_writer_teardown_success_total{mode="normal"} 41022
telemt_me_writer_teardown_noop_total 40175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81197
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.719079
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81197
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 780
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 5561481
telemt_user_connections_current{user="hello"} 2132
telemt_user_octets_from_client{user="hello"} 110876675216 (103.26 GB)
telemt_user_octets_to_client{user="hello"} 2591519204404 (2.36 TB)
telemt_user_unique_ips_current{user="hello"} 926
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 112872.7 (31h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6494224
telemt_connections_bad_total 637969
telemt_connections_current 1900
telemt_connections_me_current 1900
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 175555
telemt_upstream_connect_attempt_total 60305
telemt_upstream_connect_success_total 59854
telemt_upstream_connect_fail_total 392
telemt_upstream_connect_attempts_per_request{bucket="1"} 60246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 392
telemt_me_reconnect_attempts_total 5618
telemt_me_reconnect_success_total 1216
telemt_me_reader_eof_total 1099
telemt_me_idle_close_by_peer_total 1099
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2201976
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4952206
telemt_me_endpoint_quarantine_total 888
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 864
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 20493
telemt_desync_full_logged_total 6842
telemt_desync_suppressed_total 13651
telemt_desync_frames_bucket_total{bucket="1_2"} 5233
telemt_desync_frames_bucket_total{bucket="3_10"} 7489
telemt_desync_frames_bucket_total{bucket="gt_10"} 7771
telemt_pool_swap_total 123
telemt_pool_force_close_total 3286
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 390
telemt_me_draining_writers_reap_progress_total 38717
telemt_me_writer_removed_unexpected_total 1111
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3679
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36204
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3063
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35431
telemt_me_writer_teardown_success_total{mode="normal"} 39883
telemt_me_writer_teardown_noop_total 38721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78604
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.196576
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78604
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 390
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 951
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4955053
telemt_user_connections_current{user="hello"} 1900
telemt_user_octets_from_client{user="hello"} 93633286889 (87.20 GB)
telemt_user_octets_to_client{user="hello"} 2119984168032 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 841
telemt_user_unique_ips_recent_window{user="hello"} 210
```