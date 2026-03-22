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

# Server Metrics 2026-03-22 04:48:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 27749.0 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 455372
telemt_connections_bad_total 30747
telemt_connections_current 1087
telemt_connections_me_current 1087
telemt_handshake_timeouts_total 25465
telemt_upstream_connect_attempt_total 11513
telemt_upstream_connect_success_total 11512
telemt_upstream_connect_attempts_per_request{bucket="1"} 11512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 310
telemt_me_reconnect_success_total 181
telemt_me_reader_eof_total 177
telemt_me_idle_close_by_peer_total 177
telemt_me_route_drop_no_conn_total 94603
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375486
telemt_me_endpoint_quarantine_total 220
telemt_me_single_endpoint_shadow_rotate_total 230
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 3369
telemt_desync_full_logged_total 916
telemt_desync_suppressed_total 2453
telemt_desync_frames_bucket_total{bucket="1_2"} 1168
telemt_desync_frames_bucket_total{bucket="3_10"} 1287
telemt_desync_frames_bucket_total{bucket="gt_10"} 914
telemt_pool_swap_total 30
telemt_pool_force_close_total 793
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 10405
telemt_me_writer_removed_unexpected_total 175
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 708
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9864
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 788
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9612
telemt_me_writer_teardown_success_total{mode="normal"} 10572
telemt_me_writer_teardown_noop_total 10406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20978
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.472815
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20978
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 164
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 374548
telemt_user_connections_current{user="hello"} 1087
telemt_user_octets_from_client{user="hello"} 5091893412 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 132434984392 (123.34 GB)
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 41115.0 (11h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 906746
telemt_connections_bad_total 63775
telemt_connections_current 973
telemt_connections_me_current 973
telemt_handshake_timeouts_total 31700
telemt_upstream_connect_attempt_total 19277
telemt_upstream_connect_success_total 18974
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 19246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_reconnect_attempts_total 1609
telemt_me_reconnect_success_total 597
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 362677
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 716247
telemt_me_endpoint_quarantine_total 384
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 334
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
telemt_me_writers_active_current 43
telemt_desync_total 3054
telemt_desync_full_logged_total 1765
telemt_desync_suppressed_total 1289
telemt_desync_frames_bucket_total{bucket="1_2"} 641
telemt_desync_frames_bucket_total{bucket="3_10"} 1176
telemt_desync_frames_bucket_total{bucket="gt_10"} 1237
telemt_pool_swap_total 44
telemt_pool_force_close_total 1178
telemt_me_writer_close_signal_drop_total 85
telemt_me_draining_writers_reap_progress_total 17083
telemt_me_writer_removed_unexpected_total 503
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1429
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16169
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1156
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15905
telemt_me_writer_teardown_success_total{mode="normal"} 17598
telemt_me_writer_teardown_noop_total 17083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34681
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.075946
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34681
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 85
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 448
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 715071
telemt_user_connections_current{user="hello"} 973
telemt_user_octets_from_client{user="hello"} 11469217972 (10.68 GB)
telemt_user_octets_to_client{user="hello"} 258793129020 (241.02 GB)
telemt_user_unique_ips_current{user="hello"} 618
telemt_user_unique_ips_recent_window{user="hello"} 291
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 115974.9 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8087830
telemt_connections_bad_total 690054
telemt_connections_current 2909
telemt_connections_me_current 2909
telemt_handshake_timeouts_total 265201
telemt_upstream_connect_attempt_total 43259
telemt_upstream_connect_success_total 43181
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 43189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1638
telemt_me_reconnect_success_total 855
telemt_me_reader_eof_total 863
telemt_me_idle_close_by_peer_total 863
telemt_me_route_drop_no_conn_total 4596159
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6509073
telemt_me_endpoint_quarantine_total 745
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 870
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
telemt_desync_total 27349
telemt_desync_full_logged_total 9100
telemt_desync_suppressed_total 18249
telemt_desync_frames_bucket_total{bucket="1_2"} 5905
telemt_desync_frames_bucket_total{bucket="3_10"} 10692
telemt_desync_frames_bucket_total{bucket="gt_10"} 10752
telemt_pool_swap_total 125
telemt_pool_force_close_total 4111
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 620
telemt_me_draining_writers_reap_progress_total 39477
telemt_me_writer_removed_unexpected_total 831
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3267
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36570
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3870
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 241
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35366
telemt_me_writer_teardown_success_total{mode="normal"} 39837
telemt_me_writer_teardown_noop_total 39521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79358
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 165.335116
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79358
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 620
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 762
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6500783
telemt_user_connections_current{user="hello"} 2909
telemt_user_octets_from_client{user="hello"} 110192719256 (102.62 GB)
telemt_user_octets_to_client{user="hello"} 2193199049508 (1.99 TB)
telemt_user_unique_ips_current{user="hello"} 1234
telemt_user_unique_ips_recent_window{user="hello"} 409
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 115976.2 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6671032
telemt_connections_bad_total 597299
telemt_connections_current 2479
telemt_connections_me_current 2479
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 221543
telemt_upstream_connect_attempt_total 47199
telemt_upstream_connect_success_total 46801
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 47002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2039
telemt_me_reconnect_success_total 917
telemt_me_reader_eof_total 893
telemt_me_idle_close_by_peer_total 893
telemt_me_route_drop_no_conn_total 2305972
telemt_me_route_drop_channel_closed_total 284
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4983832
telemt_me_endpoint_quarantine_total 732
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 895
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
telemt_desync_total 23187
telemt_desync_full_logged_total 7932
telemt_desync_suppressed_total 15255
telemt_desync_frames_bucket_total{bucket="1_2"} 5567
telemt_desync_frames_bucket_total{bucket="3_10"} 9004
telemt_desync_frames_bucket_total{bucket="gt_10"} 8616
telemt_pool_swap_total 126
telemt_pool_force_close_total 3736
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 378
telemt_me_draining_writers_reap_progress_total 37916
telemt_me_writer_removed_unexpected_total 874
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35607
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3519
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 217
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34180
telemt_me_writer_teardown_success_total{mode="normal"} 38731
telemt_me_writer_teardown_noop_total 37922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76653
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.251373
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76653
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 378
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 799
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 4905454
telemt_user_connections_current{user="hello"} 2479
telemt_user_octets_from_client{user="hello"} 144808077209 (134.86 GB)
telemt_user_octets_to_client{user="hello"} 2340545301963 (2.13 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1128
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 115941.3 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6524466
telemt_connections_bad_total 555866
telemt_connections_current 2081
telemt_connections_me_current 2081
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 215988
telemt_upstream_connect_attempt_total 53618
telemt_upstream_connect_success_total 53111
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 53253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2361
telemt_me_reconnect_success_total 1033
telemt_me_reader_eof_total 976
telemt_me_idle_close_by_peer_total 976
telemt_me_route_drop_no_conn_total 2264259
telemt_me_route_drop_channel_closed_total 133
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4849985
telemt_me_endpoint_quarantine_total 821
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 862
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
telemt_me_writers_active_current 44
telemt_desync_total 23067
telemt_desync_full_logged_total 7819
telemt_desync_suppressed_total 15248
telemt_desync_frames_bucket_total{bucket="1_2"} 5629
telemt_desync_frames_bucket_total{bucket="3_10"} 8842
telemt_desync_frames_bucket_total{bucket="gt_10"} 8596
telemt_pool_swap_total 124
telemt_pool_force_close_total 3606
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 408
telemt_me_draining_writers_reap_progress_total 39033
telemt_me_writer_removed_unexpected_total 963
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3318
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36697
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3372
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 234
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35427
telemt_me_writer_teardown_success_total{mode="normal"} 40015
telemt_me_writer_teardown_noop_total 39045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79060
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.910854
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79060
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 408
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 905
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 4844814
telemt_user_connections_current{user="hello"} 2081
telemt_user_octets_from_client{user="hello"} 136190667527 (126.84 GB)
telemt_user_octets_to_client{user="hello"} 2218433269115 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 905
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 115980.3 (32h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20906071
telemt_connections_bad_total 1754520
telemt_connections_current 3472
telemt_connections_me_current 3472
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 634209
telemt_upstream_connect_attempt_total 204200
telemt_upstream_connect_success_total 185891
telemt_upstream_connect_fail_total 16474
telemt_upstream_connect_attempts_per_request{bucket="1"} 202365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8952
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16474
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65220
telemt_me_reconnect_success_total 2469
telemt_me_reader_eof_total 1556
telemt_me_idle_close_by_peer_total 1555
telemt_me_route_drop_no_conn_total 39681192
telemt_me_route_drop_channel_closed_total 129
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16810610
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 892
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 908
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
telemt_me_writers_active_current 87
telemt_desync_total 32608
telemt_desync_full_logged_total 9827
telemt_desync_suppressed_total 22781
telemt_desync_frames_bucket_total{bucket="1_2"} 7081
telemt_desync_frames_bucket_total{bucket="3_10"} 14462
telemt_desync_frames_bucket_total{bucket="gt_10"} 11065
telemt_pool_swap_total 119
telemt_pool_force_close_total 3836
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 837
telemt_me_draining_writers_reap_progress_total 36470
telemt_me_writer_removed_unexpected_total 2295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4912
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33598
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 534
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32634
telemt_me_writer_teardown_success_total{mode="normal"} 38510
telemt_me_writer_teardown_noop_total 36497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75007
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 217.276746
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75007
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 837
telemt_me_refill_failed_total 3809
telemt_me_writer_restored_same_endpoint_total 1692
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 16945296
telemt_user_connections_current{user="hello"} 3472
telemt_user_octets_from_client{user="hello"} 244666050340 (227.86 GB)
telemt_user_octets_to_client{user="hello"} 1297907911199 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1439
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 115947.1 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6300050
telemt_connections_bad_total 605674
telemt_connections_current 2488
telemt_connections_me_current 2488
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 133192
telemt_upstream_connect_attempt_total 62096
telemt_upstream_connect_success_total 61393
telemt_upstream_connect_fail_total 599
telemt_upstream_connect_attempts_per_request{bucket="1"} 61992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 599
telemt_me_reconnect_attempts_total 69848
telemt_me_reconnect_success_total 1855
telemt_me_reader_eof_total 1635
telemt_me_idle_close_by_peer_total 1634
telemt_me_route_drop_no_conn_total 2439477
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4890056
telemt_me_endpoint_quarantine_total 785
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 882
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
telemt_me_writers_active_current 44
telemt_desync_total 24380
telemt_desync_full_logged_total 8552
telemt_desync_suppressed_total 15828
telemt_desync_frames_bucket_total{bucket="1_2"} 4793
telemt_desync_frames_bucket_total{bucket="3_10"} 9424
telemt_desync_frames_bucket_total{bucket="gt_10"} 10163
telemt_pool_swap_total 120
telemt_pool_force_close_total 3428
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 408
telemt_me_draining_writers_reap_progress_total 40974
telemt_me_writer_removed_unexpected_total 1671
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4146
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38531
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3027
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37546
telemt_me_writer_teardown_success_total{mode="normal"} 42677
telemt_me_writer_teardown_noop_total 40975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83652
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.853668
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83652
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 408
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1553
telemt_me_writer_restored_fallback_total 37
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 4882356
telemt_user_connections_current{user="hello"} 2488
telemt_user_octets_from_client{user="hello"} 127900159768 (119.12 GB)
telemt_user_octets_to_client{user="hello"} 2021985860218 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1132
telemt_user_unique_ips_recent_window{user="hello"} 304
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 52783.0 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4256721
telemt_connections_bad_total 179701
telemt_connections_current 2007
telemt_connections_me_current 2007
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1690124
telemt_upstream_connect_attempt_total 30994
telemt_upstream_connect_success_total 30790
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 30987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_reconnect_attempts_total 45983
telemt_me_reconnect_success_total 1019
telemt_me_reader_eof_total 707
telemt_me_idle_close_by_peer_total 707
telemt_me_route_drop_no_conn_total 1068121
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2097565
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 410
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11293
telemt_desync_full_logged_total 3899
telemt_desync_suppressed_total 7394
telemt_desync_frames_bucket_total{bucket="1_2"} 2138
telemt_desync_frames_bucket_total{bucket="3_10"} 4326
telemt_desync_frames_bucket_total{bucket="gt_10"} 4829
telemt_pool_swap_total 57
telemt_pool_force_close_total 1672
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 19708
telemt_me_writer_removed_unexpected_total 778
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1707
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18808
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1465
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18036
telemt_me_writer_teardown_success_total{mode="normal"} 20515
telemt_me_writer_teardown_noop_total 19710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40225
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.523451
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40225
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 912
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2100783
telemt_user_connections_current{user="hello"} 2007
telemt_user_octets_from_client{user="hello"} 56967547916 (53.06 GB)
telemt_user_octets_to_client{user="hello"} 912589975342 (849.92 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 927
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 33753.7 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237581
telemt_connections_bad_total 1868
telemt_connections_current 446
telemt_connections_me_current 446
telemt_handshake_timeouts_total 6228
telemt_upstream_connect_attempt_total 16362
telemt_upstream_connect_success_total 16321
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 16358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 402
telemt_me_reconnect_success_total 224
telemt_me_reader_eof_total 225
telemt_me_idle_close_by_peer_total 225
telemt_me_route_drop_no_conn_total 66091
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211006
telemt_me_endpoint_quarantine_total 330
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 295
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
telemt_me_writers_active_current 43
telemt_desync_total 1194
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 871
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 315
telemt_pool_swap_total 37
telemt_pool_force_close_total 822
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 14816
telemt_me_writer_removed_unexpected_total 215
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 941
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14100
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 820
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13994
telemt_me_writer_teardown_success_total{mode="normal"} 15041
telemt_me_writer_teardown_noop_total 14816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29857
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.214596
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29857
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 194
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 210643
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 3560709052 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 131777253536 (122.73 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 115951.4 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7641590
telemt_connections_bad_total 764365
telemt_connections_current 2428
telemt_connections_me_current 2428
telemt_handshake_timeouts_total 217577
telemt_upstream_connect_attempt_total 45720
telemt_upstream_connect_success_total 45554
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 45683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_reconnect_attempts_total 1677
telemt_me_reconnect_success_total 895
telemt_me_reader_eof_total 887
telemt_me_idle_close_by_peer_total 887
telemt_me_route_drop_no_conn_total 2175077
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5688139
telemt_me_endpoint_quarantine_total 832
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 891
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 22246
telemt_desync_full_logged_total 7332
telemt_desync_suppressed_total 14914
telemt_desync_frames_bucket_total{bucket="1_2"} 5563
telemt_desync_frames_bucket_total{bucket="3_10"} 8091
telemt_desync_frames_bucket_total{bucket="gt_10"} 8592
telemt_pool_swap_total 128
telemt_pool_force_close_total 3413
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 404
telemt_me_draining_writers_reap_progress_total 41266
telemt_me_writer_removed_unexpected_total 852
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3216
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38927
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3325
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37853
telemt_me_writer_teardown_success_total{mode="normal"} 42143
telemt_me_writer_teardown_noop_total 41268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83411
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.798154
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83411
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 404
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 800
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5662843
telemt_user_connections_current{user="hello"} 2428
telemt_user_octets_from_client{user="hello"} 112529380484 (104.80 GB)
telemt_user_octets_to_client{user="hello"} 2640846895200 (2.40 TB)
telemt_user_unique_ips_current{user="hello"} 1042
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 115948.1 (32h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6622528
telemt_connections_bad_total 648948
telemt_connections_current 2533
telemt_connections_me_current 2533
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 179996
telemt_upstream_connect_attempt_total 61568
telemt_upstream_connect_success_total 61103
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 61508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_reconnect_attempts_total 5756
telemt_me_reconnect_success_total 1260
telemt_me_reader_eof_total 1132
telemt_me_idle_close_by_peer_total 1132
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2228952
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5057165
telemt_me_endpoint_quarantine_total 912
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 888
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
telemt_me_writers_active_current 43
telemt_desync_total 20964
telemt_desync_full_logged_total 7000
telemt_desync_suppressed_total 13964
telemt_desync_frames_bucket_total{bucket="1_2"} 5326
telemt_desync_frames_bucket_total{bucket="3_10"} 7671
telemt_desync_frames_bucket_total{bucket="gt_10"} 7967
telemt_pool_swap_total 126
telemt_pool_force_close_total 3365
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 398
telemt_me_draining_writers_reap_progress_total 39849
telemt_me_writer_removed_unexpected_total 1143
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3772
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37276
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3142
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36484
telemt_me_writer_teardown_success_total{mode="normal"} 41048
telemt_me_writer_teardown_noop_total 39853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80901
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.413753
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80901
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 398
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 986
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5059941
telemt_user_connections_current{user="hello"} 2533
telemt_user_octets_from_client{user="hello"} 95462679681 (88.91 GB)
telemt_user_octets_to_client{user="hello"} 2174396403156 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1073
telemt_user_unique_ips_recent_window{user="hello"} 294
```