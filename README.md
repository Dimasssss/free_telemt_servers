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

# Server Metrics 2026-03-21 21:10:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 223.8 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5432
telemt_connections_bad_total 78
telemt_connections_current 1007
telemt_connections_me_current 1007
telemt_handshake_timeouts_total 214
telemt_upstream_connect_attempt_total 150
telemt_upstream_connect_success_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 78
telemt_me_route_drop_no_conn_total 812
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4661
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 43
telemt_desync_total 22
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_me_draining_writers_reap_progress_total 68
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68
telemt_me_writer_teardown_success_total{mode="normal"} 68
telemt_me_writer_teardown_noop_total 68
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.033217
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136
telemt_user_connections_total{user="hello"} 4661
telemt_user_connections_current{user="hello"} 1007
telemt_user_octets_from_client{user="hello"} 23739520 (22.64 MB)
telemt_user_octets_to_client{user="hello"} 1135640008 (1.06 GB)
telemt_user_unique_ips_current{user="hello"} 375
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 13589.5 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517693
telemt_connections_bad_total 23885
telemt_connections_current 1326
telemt_connections_me_current 1326
telemt_handshake_timeouts_total 18266
telemt_upstream_connect_attempt_total 5389
telemt_upstream_connect_success_total 5280
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 5376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_reconnect_attempts_total 371
telemt_me_reconnect_success_total 166
telemt_me_reader_eof_total 144
telemt_me_idle_close_by_peer_total 144
telemt_me_route_drop_no_conn_total 290623
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420396
telemt_me_endpoint_quarantine_total 97
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_me_writers_warm_current 29
telemt_desync_total 1835
telemt_desync_full_logged_total 1047
telemt_desync_suppressed_total 788
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 700
telemt_desync_frames_bucket_total{bucket="gt_10"} 757
telemt_pool_swap_total 14
telemt_pool_force_close_total 420
telemt_me_writer_close_signal_drop_total 36
telemt_me_draining_writers_reap_progress_total 4651
telemt_me_writer_removed_unexpected_total 135
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 395
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4387
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 413
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4231
telemt_me_writer_teardown_success_total{mode="normal"} 4782
telemt_me_writer_teardown_noop_total 4651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9433
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.870981
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9433
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 36
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 115
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 419881
telemt_user_connections_current{user="hello"} 1326
telemt_user_octets_from_client{user="hello"} 6936181004 (6.46 GB)
telemt_user_octets_to_client{user="hello"} 133367656780 (124.21 GB)
telemt_user_unique_ips_current{user="hello"} 821
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 88449.4 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7027209
telemt_connections_bad_total 542933
telemt_connections_current 2110
telemt_connections_me_current 2110
telemt_handshake_timeouts_total 220366
telemt_upstream_connect_attempt_total 31759
telemt_upstream_connect_success_total 31696
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 31703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17285
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1355
telemt_me_reconnect_success_total 678
telemt_me_reader_eof_total 688
telemt_me_idle_close_by_peer_total 688
telemt_me_route_drop_no_conn_total 4400090
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5744273
telemt_me_endpoint_quarantine_total 554
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 654
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 23836
telemt_desync_full_logged_total 7939
telemt_desync_suppressed_total 15897
telemt_desync_frames_bucket_total{bucket="1_2"} 4979
telemt_desync_frames_bucket_total{bucket="3_10"} 9435
telemt_desync_frames_bucket_total{bucket="gt_10"} 9422
telemt_pool_swap_total 95
telemt_pool_force_close_total 3221
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 523
telemt_me_draining_writers_reap_progress_total 28942
telemt_me_writer_removed_unexpected_total 661
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2477
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26718
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2988
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25721
telemt_me_writer_teardown_success_total{mode="normal"} 29195
telemt_me_writer_teardown_noop_total 28979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58174
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 143.349396
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58174
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 523
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 607
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 5737334
telemt_user_connections_current{user="hello"} 2110
telemt_user_octets_from_client{user="hello"} 99015496928 (92.22 GB)
telemt_user_octets_to_client{user="hello"} 1822592847620 (1.66 TB)
telemt_user_unique_ips_current{user="hello"} 846
telemt_user_unique_ips_recent_window{user="hello"} 334
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 88450.9 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5701951
telemt_connections_bad_total 555103
telemt_connections_current 2884
telemt_connections_me_current 2884
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 186465
telemt_upstream_connect_attempt_total 35808
telemt_upstream_connect_success_total 35486
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 35654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1681
telemt_me_reconnect_success_total 706
telemt_me_reader_eof_total 682
telemt_me_idle_close_by_peer_total 682
telemt_me_route_drop_no_conn_total 1968675
telemt_me_route_drop_channel_closed_total 226
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4262086
telemt_me_endpoint_quarantine_total 540
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 674
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 20412
telemt_desync_full_logged_total 6796
telemt_desync_suppressed_total 13616
telemt_desync_frames_bucket_total{bucket="1_2"} 4975
telemt_desync_frames_bucket_total{bucket="3_10"} 7899
telemt_desync_frames_bucket_total{bucket="gt_10"} 7538
telemt_pool_swap_total 97
telemt_pool_force_close_total 2949
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 333
telemt_me_draining_writers_reap_progress_total 27627
telemt_me_writer_removed_unexpected_total 659
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2394
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25823
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2750
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24678
telemt_me_writer_teardown_success_total{mode="normal"} 28217
telemt_me_writer_teardown_noop_total 27632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55849
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.697980
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55849
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 333
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 606
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4253854
telemt_user_connections_current{user="hello"} 2884
telemt_user_octets_from_client{user="hello"} 128589366545 (119.76 GB)
telemt_user_octets_to_client{user="hello"} 1960907306655 (1.78 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1102
telemt_user_unique_ips_recent_window{user="hello"} 417
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 88414.6 (24h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5628837
telemt_connections_bad_total 508425
telemt_connections_current 2354
telemt_connections_me_current 2354
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 172105
telemt_upstream_connect_attempt_total 42241
telemt_upstream_connect_success_total 41962
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 42097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1041
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1735
telemt_me_reconnect_success_total 768
telemt_me_reader_eof_total 712
telemt_me_idle_close_by_peer_total 712
telemt_me_route_drop_no_conn_total 2025484
telemt_me_route_drop_channel_closed_total 104
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4246626
telemt_me_endpoint_quarantine_total 597
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 659
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 43
telemt_desync_total 20172
telemt_desync_full_logged_total 6617
telemt_desync_suppressed_total 13555
telemt_desync_frames_bucket_total{bucket="1_2"} 5017
telemt_desync_frames_bucket_total{bucket="3_10"} 7634
telemt_desync_frames_bucket_total{bucket="gt_10"} 7521
telemt_pool_swap_total 95
telemt_pool_force_close_total 2823
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 338
telemt_me_draining_writers_reap_progress_total 29090
telemt_me_writer_removed_unexpected_total 682
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2483
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27292
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2610
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26267
telemt_me_writer_teardown_success_total{mode="normal"} 29775
telemt_me_writer_teardown_noop_total 29100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58875
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.405103
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58875
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 338
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 664
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4248551
telemt_user_connections_current{user="hello"} 2354
telemt_user_octets_from_client{user="hello"} 123970918631 (115.46 GB)
telemt_user_octets_to_client{user="hello"} 1937909486451 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 908
telemt_user_unique_ips_recent_window{user="hello"} 449
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 88454.1 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19292528
telemt_connections_bad_total 1280057
telemt_connections_current 3392
telemt_connections_me_current 3392
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 540228
telemt_upstream_connect_attempt_total 181848
telemt_upstream_connect_success_total 164585
telemt_upstream_connect_fail_total 15808
telemt_upstream_connect_attempts_per_request{bucket="1"} 180393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8850
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15808
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59650
telemt_me_reconnect_success_total 1904
telemt_me_reader_eof_total 1256
telemt_me_idle_close_by_peer_total 1255
telemt_me_route_drop_no_conn_total 39180333
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15841115
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 653
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 688
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 29879
telemt_desync_full_logged_total 8816
telemt_desync_suppressed_total 21063
telemt_desync_frames_bucket_total{bucket="1_2"} 6552
telemt_desync_frames_bucket_total{bucket="3_10"} 13243
telemt_desync_frames_bucket_total{bucket="gt_10"} 10084
telemt_pool_swap_total 90
telemt_pool_force_close_total 3027
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 694
telemt_me_draining_writers_reap_progress_total 27318
telemt_me_writer_removed_unexpected_total 1794
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3738
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25118
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2537
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 490
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24291
telemt_me_writer_teardown_success_total{mode="normal"} 28856
telemt_me_writer_teardown_noop_total 27344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56200
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 205.040318
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56200
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 694
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1328
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14223
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 15966218
telemt_user_connections_current{user="hello"} 3392
telemt_user_octets_from_client{user="hello"} 158072172286 (147.22 GB)
telemt_user_octets_to_client{user="hello"} 990532668386 (922.51 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1343
telemt_user_unique_ips_recent_window{user="hello"} 513
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 88421.7 (24h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5511518
telemt_connections_bad_total 526335
telemt_connections_current 2001
telemt_connections_me_current 2001
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 113565
telemt_upstream_connect_attempt_total 45380
telemt_upstream_connect_success_total 44882
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 45295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_reconnect_attempts_total 11118
telemt_me_reconnect_success_total 1281
telemt_me_reader_eof_total 1210
telemt_me_idle_close_by_peer_total 1210
telemt_me_route_drop_no_conn_total 2290297
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4283725
telemt_me_endpoint_quarantine_total 542
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 660
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 21327
telemt_desync_full_logged_total 7397
telemt_desync_suppressed_total 13930
telemt_desync_frames_bucket_total{bucket="1_2"} 4073
telemt_desync_frames_bucket_total{bucket="3_10"} 8293
telemt_desync_frames_bucket_total{bucket="gt_10"} 8961
telemt_pool_swap_total 90
telemt_pool_force_close_total 2670
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 336
telemt_me_draining_writers_reap_progress_total 29909
telemt_me_writer_removed_unexpected_total 1190
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3044
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28068
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2304
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 366
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27239
telemt_me_writer_teardown_success_total{mode="normal"} 31112
telemt_me_writer_teardown_noop_total 29910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61022
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.510580
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61022
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 336
telemt_me_refill_failed_total 593
telemt_me_writer_restored_same_endpoint_total 1082
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4273264
telemt_user_connections_current{user="hello"} 2001
telemt_user_octets_from_client{user="hello"} 114320713449 (106.47 GB)
telemt_user_octets_to_client{user="hello"} 1735048202303 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 764
telemt_user_unique_ips_recent_window{user="hello"} 716
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 25257.5 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3254683
telemt_connections_bad_total 119897
telemt_connections_current 3152
telemt_connections_me_current 3152
telemt_handshake_timeouts_total 1386409
telemt_upstream_connect_attempt_total 8239
telemt_upstream_connect_success_total 8132
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 8233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_reconnect_attempts_total 2219
telemt_me_reconnect_success_total 277
telemt_me_reader_eof_total 217
telemt_me_idle_close_by_peer_total 217
telemt_me_route_drop_no_conn_total 934855
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1551971
telemt_me_endpoint_quarantine_total 123
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_warm_current 21
telemt_desync_total 8603
telemt_desync_full_logged_total 2865
telemt_desync_suppressed_total 5738
telemt_desync_frames_bucket_total{bucket="1_2"} 1542
telemt_desync_frames_bucket_total{bucket="3_10"} 3266
telemt_desync_frames_bucket_total{bucket="gt_10"} 3795
telemt_pool_swap_total 26
telemt_pool_force_close_total 846
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 7137
telemt_me_writer_removed_unexpected_total 234
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 668
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6711
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 737
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 109
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6291
telemt_me_writer_teardown_success_total{mode="normal"} 7379
telemt_me_writer_teardown_noop_total 7138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14517
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.186127
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14517
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 226
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1547541
telemt_user_connections_current{user="hello"} 3152
telemt_user_octets_from_client{user="hello"} 45546202512 (42.42 GB)
telemt_user_octets_to_client{user="hello"} 652506435668 (607.69 GB)
telemt_user_unique_ips_current{user="hello"} 1355
telemt_user_unique_ips_recent_window{user="hello"} 602
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 6228.4 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74385
telemt_connections_bad_total 490
telemt_connections_current 1514
telemt_connections_me_current 1514
telemt_handshake_timeouts_total 1319
telemt_upstream_connect_attempt_total 2654
telemt_upstream_connect_success_total 2645
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 2652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 63
telemt_me_reconnect_success_total 32
telemt_me_reader_eof_total 32
telemt_me_idle_close_by_peer_total 32
telemt_me_route_drop_no_conn_total 20823
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64115
telemt_me_endpoint_quarantine_total 39
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 479
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 339
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 6
telemt_pool_force_close_total 160
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 2297
telemt_me_writer_removed_unexpected_total 32
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2178
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 160
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2137
telemt_me_writer_teardown_success_total{mode="normal"} 2329
telemt_me_writer_teardown_noop_total 2297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4626
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.304038
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4626
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 64022
telemt_user_connections_current{user="hello"} 1514
telemt_user_octets_from_client{user="hello"} 1323127392 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 46181522708 (43.01 GB)
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 88426.5 (24h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6546813
telemt_connections_bad_total 666005
telemt_connections_current 3000
telemt_connections_me_current 3000
telemt_handshake_timeouts_total 188855
telemt_upstream_connect_attempt_total 33508
telemt_upstream_connect_success_total 33373
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 33471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_reconnect_attempts_total 1408
telemt_me_reconnect_success_total 713
telemt_me_reader_eof_total 688
telemt_me_idle_close_by_peer_total 688
telemt_me_route_drop_no_conn_total 2018340
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5017945
telemt_me_endpoint_quarantine_total 591
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 674
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 19144
telemt_desync_full_logged_total 6387
telemt_desync_suppressed_total 12757
telemt_desync_frames_bucket_total{bucket="1_2"} 4661
telemt_desync_frames_bucket_total{bucket="3_10"} 6973
telemt_desync_frames_bucket_total{bucket="gt_10"} 7510
telemt_pool_swap_total 98
telemt_pool_force_close_total 2682
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 337
telemt_me_draining_writers_reap_progress_total 30090
telemt_me_writer_removed_unexpected_total 670
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2444
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28324
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2597
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27408
telemt_me_writer_teardown_success_total{mode="normal"} 30768
telemt_me_writer_teardown_noop_total 30092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60860
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.874197
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60860
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 337
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 637
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4993701
telemt_user_connections_current{user="hello"} 3000
telemt_user_octets_from_client{user="hello"} 99461688260 (92.63 GB)
telemt_user_octets_to_client{user="hello"} 2337875652816 (2.13 TB)
telemt_user_unique_ips_current{user="hello"} 1054
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 88423.2 (24h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5563470
telemt_connections_bad_total 522106
telemt_connections_current 2820
telemt_connections_me_current 2820
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 159476
telemt_upstream_connect_attempt_total 49819
telemt_upstream_connect_success_total 49448
telemt_upstream_connect_fail_total 312
telemt_upstream_connect_attempts_per_request{bucket="1"} 49760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 312
telemt_me_reconnect_attempts_total 4531
telemt_me_reconnect_success_total 1001
telemt_me_reader_eof_total 887
telemt_me_idle_close_by_peer_total 887
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2073922
telemt_me_route_drop_channel_closed_total 187
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4382958
telemt_me_endpoint_quarantine_total 699
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 671
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_active_current 43
telemt_desync_total 17829
telemt_desync_full_logged_total 6014
telemt_desync_suppressed_total 11815
telemt_desync_frames_bucket_total{bucket="1_2"} 4409
telemt_desync_frames_bucket_total{bucket="3_10"} 6550
telemt_desync_frames_bucket_total{bucket="gt_10"} 6870
telemt_pool_swap_total 96
telemt_pool_force_close_total 2617
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 334
telemt_me_draining_writers_reap_progress_total 29236
telemt_me_writer_removed_unexpected_total 898
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2928
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27248
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2417
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 200
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26619
telemt_me_writer_teardown_success_total{mode="normal"} 30176
telemt_me_writer_teardown_noop_total 29240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59416
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.042055
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59416
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 334
telemt_me_refill_failed_total 201
telemt_me_writer_restored_same_endpoint_total 770
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 4386874
telemt_user_connections_current{user="hello"} 2820
telemt_user_octets_from_client{user="hello"} 83892498105 (78.13 GB)
telemt_user_octets_to_client{user="hello"} 1849055369112 (1.68 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1104
telemt_user_unique_ips_recent_window{user="hello"} 465
```