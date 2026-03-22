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

# Server Metrics 2026-03-22 15:33:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 66430.4 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2317378
telemt_connections_bad_total 124937
telemt_connections_current 1691
telemt_connections_me_current 1691
telemt_handshake_timeouts_total 85941
telemt_upstream_connect_attempt_total 24590
telemt_upstream_connect_success_total 24589
telemt_upstream_connect_attempts_per_request{bucket="1"} 24589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1014
telemt_me_reconnect_success_total 423
telemt_me_reader_eof_total 425
telemt_me_idle_close_by_peer_total 425
telemt_me_route_drop_no_conn_total 1867014
telemt_me_route_drop_channel_closed_total 750
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1967033
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 453
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 521
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 9772
telemt_desync_full_logged_total 3016
telemt_desync_suppressed_total 6756
telemt_desync_frames_bucket_total{bucket="1_2"} 2639
telemt_desync_frames_bucket_total{bucket="3_10"} 3661
telemt_desync_frames_bucket_total{bucket="gt_10"} 3472
telemt_pool_swap_total 73
telemt_pool_force_close_total 2247
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 418
telemt_me_draining_writers_reap_progress_total 22447
telemt_me_writer_removed_unexpected_total 412
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1630
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21030
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2200
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20200
telemt_me_writer_teardown_success_total{mode="normal"} 22660
telemt_me_writer_teardown_noop_total 22453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45113
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 198.641197
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45113
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 418
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 373
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1963755
telemt_user_connections_current{user="hello"} 1691
telemt_user_octets_from_client{user="hello"} 29752700204 (27.71 GB)
telemt_user_octets_to_client{user="hello"} 528072257328 (491.81 GB)
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 79796.6 (22h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3532717
telemt_connections_bad_total 321745
telemt_connections_current 1296
telemt_connections_me_current 1296
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 84613
telemt_upstream_connect_attempt_total 50434
telemt_upstream_connect_success_total 49820
telemt_upstream_connect_fail_total 542
telemt_upstream_connect_attempts_per_request{bucket="1"} 50362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 542
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5724
telemt_me_reconnect_success_total 1992
telemt_me_reader_eof_total 1921
telemt_me_idle_close_by_peer_total 1921
telemt_me_route_drop_no_conn_total 3511780
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2799471
telemt_me_endpoint_quarantine_total 643
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 618
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_me_writers_active_current 87
telemt_desync_total 10809
telemt_desync_full_logged_total 6004
telemt_desync_suppressed_total 4805
telemt_desync_frames_bucket_total{bucket="1_2"} 2537
telemt_desync_frames_bucket_total{bucket="3_10"} 4267
telemt_desync_frames_bucket_total{bucket="gt_10"} 4005
telemt_pool_swap_total 75
telemt_pool_force_close_total 2228
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 31654
telemt_me_writer_removed_unexpected_total 1877
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3685
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29849
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 318
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29426
telemt_me_writer_teardown_success_total{mode="normal"} 33534
telemt_me_writer_teardown_noop_total 31654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65188
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.581255
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65188
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1702
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 2810829
telemt_user_connections_current{user="hello"} 1296
telemt_user_octets_from_client{user="hello"} 34372546063 (32.01 GB)
telemt_user_octets_to_client{user="hello"} 613460156414 (571.33 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 713
telemt_user_unique_ips_recent_window{user="hello"} 333
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 154656.4 (42h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15148134
telemt_connections_bad_total 1389764
telemt_connections_current 2239
telemt_connections_me_current 2239
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 368056
telemt_upstream_connect_attempt_total 70145
telemt_upstream_connect_success_total 70050
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 70067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1665
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2585
telemt_me_reconnect_success_total 1333
telemt_me_reader_eof_total 1270
telemt_me_idle_close_by_peer_total 1269
telemt_me_route_drop_no_conn_total 13746861
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12121920
telemt_me_endpoint_quarantine_total 974
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1152
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 49035
telemt_desync_full_logged_total 15389
telemt_desync_suppressed_total 33646
telemt_desync_frames_bucket_total{bucket="1_2"} 11016
telemt_desync_frames_bucket_total{bucket="3_10"} 19182
telemt_desync_frames_bucket_total{bucket="gt_10"} 18837
telemt_pool_swap_total 166
telemt_pool_force_close_total 5663
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 924
telemt_me_draining_writers_reap_progress_total 50856
telemt_me_writer_removed_unexpected_total 1226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4425
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46962
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5204
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 459
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45193
telemt_me_writer_teardown_success_total{mode="normal"} 51387
telemt_me_writer_teardown_noop_total 50906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102293
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 291.564127
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102293
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 924
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 1144
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 12123367
telemt_user_connections_current{user="hello"} 2239
telemt_user_octets_from_client{user="hello"} 170570238269 (158.86 GB)
telemt_user_octets_to_client{user="hello"} 3115567135411 (2.83 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 892
telemt_user_unique_ips_recent_window{user="hello"} 374
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 154658.0 (42h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10924852
telemt_connections_bad_total 1054252
telemt_connections_current 1574
telemt_connections_me_current 1574
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 323243
telemt_upstream_connect_attempt_total 82321
telemt_upstream_connect_success_total 81169
telemt_upstream_connect_fail_total 828
telemt_upstream_connect_attempts_per_request{bucket="1"} 81997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 828
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3892
telemt_me_reconnect_success_total 1575
telemt_me_reader_eof_total 1442
telemt_me_idle_close_by_peer_total 1442
telemt_me_route_drop_no_conn_total 4329247
telemt_me_route_drop_channel_closed_total 477
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8154917
telemt_me_endpoint_quarantine_total 972
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1171
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 36188
telemt_desync_full_logged_total 12151
telemt_desync_suppressed_total 24037
telemt_desync_frames_bucket_total{bucket="1_2"} 8873
telemt_desync_frames_bucket_total{bucket="3_10"} 13936
telemt_desync_frames_bucket_total{bucket="gt_10"} 13379
telemt_pool_swap_total 164
telemt_pool_force_close_total 5097
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 658
telemt_me_draining_writers_reap_progress_total 49146
telemt_me_writer_removed_unexpected_total 1474
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4537
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45940
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4625
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 472
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44049
telemt_me_writer_teardown_success_total{mode="normal"} 50477
telemt_me_writer_teardown_noop_total 49164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99641
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.059085
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99641
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 658
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 1338
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 8093761
telemt_user_connections_current{user="hello"} 1574
telemt_user_octets_from_client{user="hello"} 203174536425 (189.22 GB)
telemt_user_octets_to_client{user="hello"} 3648595661262 (3.32 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 596
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 154622.0 (42h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10353354
telemt_connections_bad_total 886520
telemt_connections_current 1338
telemt_connections_me_current 1338
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 330030
telemt_upstream_connect_attempt_total 67547
telemt_upstream_connect_success_total 66620
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 66802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4619
telemt_me_reconnect_success_total 1862
telemt_me_reader_eof_total 1619
telemt_me_idle_close_by_peer_total 1618
telemt_me_route_drop_no_conn_total 5102148
telemt_me_route_drop_channel_closed_total 353
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7818111
telemt_me_endpoint_quarantine_total 1059
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 1136
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_active_current 45
telemt_desync_total 35822
telemt_desync_full_logged_total 11872
telemt_desync_suppressed_total 23950
telemt_desync_frames_bucket_total{bucket="1_2"} 9057
telemt_desync_frames_bucket_total{bucket="3_10"} 13691
telemt_desync_frames_bucket_total{bucket="gt_10"} 13074
telemt_pool_swap_total 161
telemt_pool_force_close_total 5048
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 49604
telemt_me_writer_removed_unexpected_total 1759
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4975
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46300
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4511
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 537
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44556
telemt_me_writer_teardown_success_total{mode="normal"} 51275
telemt_me_writer_teardown_noop_total 49675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100950
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3169.945334
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100950
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1613
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 7811194
telemt_user_connections_current{user="hello"} 1338
telemt_user_octets_from_client{user="hello"} 180381075905 (167.99 GB)
telemt_user_octets_to_client{user="hello"} 3244666718601 (2.95 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 536
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 24902.0 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9969920
telemt_connections_bad_total 610386
telemt_connections_current 2164
telemt_connections_me_current 2164
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 168372
telemt_upstream_connect_attempt_total 34557
telemt_upstream_connect_success_total 32817
telemt_upstream_connect_fail_total 1245
telemt_upstream_connect_attempts_per_request{bucket="1"} 34062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1245
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5691
telemt_me_reconnect_success_total 670
telemt_me_reader_eof_total 414
telemt_me_idle_close_by_peer_total 414
telemt_me_route_drop_no_conn_total 24836345
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8310646
telemt_me_endpoint_quarantine_total 157
telemt_me_single_endpoint_outage_enter_total 47
telemt_me_single_endpoint_outage_exit_total 47
telemt_me_single_endpoint_outage_reconnect_attempt_total 81
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 81
telemt_me_single_endpoint_shadow_rotate_total 194
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 12618
telemt_desync_full_logged_total 3236
telemt_desync_suppressed_total 9382
telemt_desync_frames_bucket_total{bucket="1_2"} 2178
telemt_desync_frames_bucket_total{bucket="3_10"} 5129
telemt_desync_frames_bucket_total{bucket="gt_10"} 5311
telemt_pool_swap_total 23
telemt_pool_force_close_total 953
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 355
telemt_me_draining_writers_reap_progress_total 6661
telemt_me_writer_removed_unexpected_total 576
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1160
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6041
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 679
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5708
telemt_me_writer_teardown_success_total{mode="normal"} 7201
telemt_me_writer_teardown_noop_total 6666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13867
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 31.165113
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13867
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 355
telemt_me_refill_failed_total 285
telemt_me_writer_restored_same_endpoint_total 457
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 8328952
telemt_user_connections_current{user="hello"} 2164
telemt_user_octets_from_client{user="hello"} 54651170442 (50.90 GB)
telemt_user_octets_to_client{user="hello"} 257809149488 (240.10 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 796
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 154628.7 (42h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10102294
telemt_connections_bad_total 841740
telemt_connections_current 1903
telemt_connections_me_current 1903
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 221959
telemt_upstream_connect_attempt_total 92369
telemt_upstream_connect_success_total 91414
telemt_upstream_connect_fail_total 812
telemt_upstream_connect_attempts_per_request{bucket="1"} 92226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33727
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1267
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 812
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71588
telemt_me_reconnect_success_total 2563
telemt_me_reader_eof_total 2275
telemt_me_idle_close_by_peer_total 2274
telemt_me_route_drop_no_conn_total 5027353
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7976177
telemt_me_endpoint_quarantine_total 1037
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1151
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 41377
telemt_desync_full_logged_total 14136
telemt_desync_suppressed_total 27241
telemt_desync_frames_bucket_total{bucket="1_2"} 8415
telemt_desync_frames_bucket_total{bucket="3_10"} 16046
telemt_desync_frames_bucket_total{bucket="gt_10"} 16916
telemt_pool_swap_total 157
telemt_pool_force_close_total 4704
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 576
telemt_me_draining_writers_reap_progress_total 52644
telemt_me_writer_removed_unexpected_total 2320
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5614
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49369
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 679
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47940
telemt_me_writer_teardown_success_total{mode="normal"} 54983
telemt_me_writer_teardown_noop_total 52645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107628
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.330922
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107628
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 576
telemt_me_refill_failed_total 4258
telemt_me_writer_restored_same_endpoint_total 2159
telemt_me_writer_restored_fallback_total 43
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 7976397
telemt_user_connections_current{user="hello"} 1903
telemt_user_octets_from_client{user="hello"} 180903651495 (168.48 GB)
telemt_user_octets_to_client{user="hello"} 2998532983549 (2.73 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 711
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 91464.7 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10496866
telemt_connections_bad_total 385767
telemt_connections_current 1462
telemt_connections_me_current 1462
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4430787
telemt_upstream_connect_attempt_total 44263
telemt_upstream_connect_success_total 43938
telemt_upstream_connect_fail_total 316
telemt_upstream_connect_attempts_per_request{bucket="1"} 44254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 316
telemt_me_reconnect_attempts_total 48034
telemt_me_reconnect_success_total 1498
telemt_me_reader_eof_total 1161
telemt_me_idle_close_by_peer_total 1160
telemt_me_route_drop_no_conn_total 3885233
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5028418
telemt_me_endpoint_quarantine_total 598
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 688
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 27471
telemt_desync_full_logged_total 9265
telemt_desync_suppressed_total 18206
telemt_desync_frames_bucket_total{bucket="1_2"} 5546
telemt_desync_frames_bucket_total{bucket="3_10"} 10856
telemt_desync_frames_bucket_total{bucket="gt_10"} 11069
telemt_pool_swap_total 96
telemt_pool_force_close_total 2981
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 309
telemt_me_draining_writers_reap_progress_total 31391
telemt_me_writer_removed_unexpected_total 1224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2842
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29803
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2562
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28410
telemt_me_writer_teardown_success_total{mode="normal"} 32645
telemt_me_writer_teardown_noop_total 31398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64043
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.608787
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64043
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 309
telemt_me_refill_failed_total 2705
telemt_me_writer_restored_same_endpoint_total 1332
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5022098
telemt_user_connections_current{user="hello"} 1462
telemt_user_octets_from_client{user="hello"} 108475256848 (101.03 GB)
telemt_user_octets_to_client{user="hello"} 1891033007842 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 72435.5 (20h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 935336
telemt_connections_bad_total 12500
telemt_connections_current 1150
telemt_connections_me_current 1150
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18278
telemt_upstream_connect_attempt_total 35896
telemt_upstream_connect_success_total 35806
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 35880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 496
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 1615
telemt_me_reconnect_success_total 683
telemt_me_reader_eof_total 658
telemt_me_idle_close_by_peer_total 658
telemt_me_route_drop_no_conn_total 320594
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 832045
telemt_me_endpoint_quarantine_total 634
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 601
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 4594
telemt_desync_full_logged_total 1403
telemt_desync_suppressed_total 3191
telemt_desync_frames_bucket_total{bucket="1_2"} 1081
telemt_desync_frames_bucket_total{bucket="3_10"} 1820
telemt_desync_frames_bucket_total{bucket="gt_10"} 1693
telemt_pool_swap_total 77
telemt_pool_force_close_total 1938
telemt_me_writer_close_signal_drop_total 111
telemt_me_draining_writers_reap_progress_total 29670
telemt_me_writer_removed_unexpected_total 636
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2293
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28037
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1860
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27732
telemt_me_writer_teardown_success_total{mode="normal"} 30330
telemt_me_writer_teardown_noop_total 29672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60002
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.472625
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60002
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 111
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 582
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 833095
telemt_user_connections_current{user="hello"} 1150
telemt_user_octets_from_client{user="hello"} 15187997473 (14.14 GB)
telemt_user_octets_to_client{user="hello"} 378253947379 (352.28 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 154633.1 (42h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12390225
telemt_connections_bad_total 1440433
telemt_connections_current 1971
telemt_connections_me_current 1971
telemt_handshake_timeouts_total 339545
telemt_upstream_connect_attempt_total 57879
telemt_upstream_connect_success_total 57652
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 57829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_reconnect_attempts_total 2261
telemt_me_reconnect_success_total 1204
telemt_me_reader_eof_total 1169
telemt_me_idle_close_by_peer_total 1169
telemt_me_route_drop_no_conn_total 4136577
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9360562
telemt_me_endpoint_quarantine_total 1045
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1153
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 38365
telemt_desync_full_logged_total 12533
telemt_desync_suppressed_total 25832
telemt_desync_frames_bucket_total{bucket="1_2"} 9119
telemt_desync_frames_bucket_total{bucket="3_10"} 14220
telemt_desync_frames_bucket_total{bucket="gt_10"} 15026
telemt_pool_swap_total 171
telemt_pool_force_close_total 4736
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 609
telemt_me_draining_writers_reap_progress_total 52127
telemt_me_writer_removed_unexpected_total 1123
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4283
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48999
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4563
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47391
telemt_me_writer_teardown_success_total{mode="normal"} 53282
telemt_me_writer_teardown_noop_total 52129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105411
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.878617
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105411
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 609
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1054
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9329935
telemt_user_connections_current{user="hello"} 1971
telemt_user_octets_from_client{user="hello"} 181363449556 (168.91 GB)
telemt_user_octets_to_client{user="hello"} 4122813061040 (3.75 TB)
telemt_user_unique_ips_current{user="hello"} 714
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 154629.7 (42h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10731590
telemt_connections_bad_total 1198277
telemt_connections_current 1643
telemt_connections_me_current 1643
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 277124
telemt_upstream_connect_attempt_total 83692
telemt_upstream_connect_success_total 83068
telemt_upstream_connect_fail_total 540
telemt_upstream_connect_attempts_per_request{bucket="1"} 83608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34385
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2028
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 540
telemt_me_reconnect_attempts_total 8830
telemt_me_reconnect_success_total 2031
telemt_me_reader_eof_total 1897
telemt_me_idle_close_by_peer_total 1897
telemt_me_seq_mismatch_total 73
telemt_me_route_drop_no_conn_total 5384850
telemt_me_route_drop_channel_closed_total 344
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8293619
telemt_me_endpoint_quarantine_total 1172
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1158
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 37972
telemt_desync_full_logged_total 12265
telemt_desync_suppressed_total 25707
telemt_desync_frames_bucket_total{bucket="1_2"} 9447
telemt_desync_frames_bucket_total{bucket="3_10"} 14155
telemt_desync_frames_bucket_total{bucket="gt_10"} 14370
telemt_pool_swap_total 163
telemt_pool_force_close_total 4582
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 597
telemt_me_draining_writers_reap_progress_total 51618
telemt_me_writer_removed_unexpected_total 1923
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5379
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48229
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4143
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47036
telemt_me_writer_teardown_success_total{mode="normal"} 53608
telemt_me_writer_teardown_noop_total 51623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105231
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.319784
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105231
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 597
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 1653
telemt_me_writer_restored_fallback_total 99
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8299686
telemt_user_connections_current{user="hello"} 1643
telemt_user_octets_from_client{user="hello"} 146282016133 (136.24 GB)
telemt_user_octets_to_client{user="hello"} 3166875117291 (2.88 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 616
telemt_user_unique_ips_recent_window{user="hello"} 253
```